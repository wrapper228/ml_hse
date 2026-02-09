# Methods used in Seminars and Lectures

## Numpy
- `np.array`
- `np.sum` (and method `.sum()`)
- `np.sin`, `np.cos`
- `np.dot`, `@`
- `np.arange`
- `np.zeros`, `np.ones`, `np.identity`
- `np.hstack`, `np.vstack`
- `np.random.rand`, `np.random.randn`, `np.random.normal`, `np.random.randint`, `np.random.seed`
- `np.abs`
- `np.argmin`, `np.argmax`
- `np.append`
- `np.where` (implied usage for masking/indexing conceptually, explicit in HW solutions)
- `.reshape`, `.T`, `.transpose`
- `.ndim`, `.shape`, `.dtype`

## Pandas
### Series
- `pd.Series`
- `s.astype`
- `s.values`
- `s.index`
- `s.name`
- `s.unique`
- `s.str` accessor (`upper`, `split`)
- `s.value_counts`
- `s.isin`

### DataFrame
- `pd.DataFrame`
- `df.head`, `df.tail`, `df.sample`
- `df.columns`, `df.index`, `df.shape`, `df.dtypes`
- `df.info`, `df.describe`
- `df.astype`
- `df.to_numpy`
- `df.isna`, `df.dropna`, `df.fillna` (method='bfill', 'ffill')
- `df.mean`, `df.std`, `df.var`, `df.value_counts`, `df.corr`
- `df.apply`
- `df.T`
- `df.set_index`, `df.reset_index`
- `df.sort_values`, `df.sort_index`
- `df.loc`, `df.iloc`, `df.at`
- `df.groupby`
    - `.mean()`, `.max()`, `.min()`
    - `.agg()`
    - `.apply()`
    - `.rank()`
- `df.unstack`, `df.stack`
- `df.pivot_table`
- `pd.read_csv`, `df.to_csv`
- `pd.concat`, `pd.merge`, `pd.join`
- `pd.crosstab`

## Matplotlib
- `plt.plot`, `plt.scatter`, `plt.bar`, `plt.hist`
- `plt.figure`, `plt.subplot`, `plt.subplots`
- `plt.title`, `plt.xlabel`, `plt.ylabel`, `plt.legend`, `plt.text`, `plt.grid`
- `plt.show`
- `plt.setp`
- Object-oriented API:
    - `ax.plot`, `ax.scatter`, `ax.hist`, `ax.bar`, `ax.imshow`
    - `ax.set_xlabel`, `ax.set_ylabel`, `ax.set_xlim`
    - `ax.set_xticks`, `ax.set_yticks`, `ax.set_xticklabels`, `ax.set_yticklabels`
    - `ax.tick_params`
    - `ax.twinx`

## Seaborn
- `sns.heatmap`
- `sns.displot`
- `sns.jointplot`
- `sns.pairplot`
- `sns.FacetGrid`
- `sns.barplot`, `sns.countplot`
- `sns.boxplot`, `sns.violinplot`
- `sns.load_dataset`
