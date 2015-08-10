# conventions
Les conventions de Buddyweb

## Code général (tous languages)

** Sauts de ligne **

Un saut de ligne doit toujours être justifié. On saute toujours une ligne et jamais deux.

Exemple :
		
  public function show($id)
  {
  	$company = Company::find($id);
  	$company['workplaces'] = $company->workplaces()->get(['name']);
  	$company['sectors'] = $company->sectors()->get(['name']);
  	$company['products'] = $company->products;
  
  	return $company;
  }




