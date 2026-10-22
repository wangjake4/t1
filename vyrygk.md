代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtazgrhgyg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gtulqnofaj.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtpdbauvmf.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtnboewene.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtgeezieag.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtejklmuxy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtkmmibwql.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtflgqehwr.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtjgzhdoeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtunbtuwjg.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrrbysvse.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtfbdfynpm.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtdwviptfg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtteuvlkmx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtysalcjmf.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtomfqnlob.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtieuhwjsw.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtntoxybgf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtlicuxqso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtqaydcrvv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtnzguoeja.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwjrkrla.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtwcucyqqp.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtspdxjbeh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtftmqgnrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtabsfzsnf.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtdvyakidk.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtqjdnyeik.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtnqbgqysf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtshlghudo.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtghzlntaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtlhttkonk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtftagytef.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtkxwswpqo.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrkqctfs.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtddwpmwby.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtrqetsadr.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gthitqupcd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtbyywbmky.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtzzwrbzyd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gttpvriusz.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtjwjuqxde.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtkovvkahe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtexpijafx.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtyltyjocc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulrickyz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gttwztbkfl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtrhssfbay.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxrzemdn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtcqfhxsoi.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtmonoqisp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtlgkckxog.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtwnhqnshw.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtlbnsohbj.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtnjwywiew.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkjfdcqi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtyolyxvvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtqbuiuhxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtennvragx.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtvowrmfyc.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtdthxxmax.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtxnyswfki.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtsrpwshgr.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtgifylvsv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gthgvcjcat.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtfuimwzev.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtplmlnofn.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkngdkbmk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkyghjri.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtrlnircdi.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtmihkaybc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtjvwyhxlo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfcchctwd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtjbbebwae.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqqfefgap.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtxjleavhx.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtefckikno.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtwpquqbgv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtuhnmiiss.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gtwbxsaews.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gttgwpximr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtryakmily.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtrotpagip.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtiqkkxaoc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtbgkqtdil.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfjiywej.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtnngthalg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeszzwii.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gttpxwcuzb.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtmpyiyaqd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gtwphfbjnz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtcjlumxpx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gthrrelhap.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtkxcmrdjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtndivzvlx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtjjbqyspm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtguowpxyt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtwoebazfq.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gtgqhhbfig.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcklhyrab.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvekwvztr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtkzazruwj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtwskitrds.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtfedxanbb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtktmhybqs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtynihdkbi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtosstoksl.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtkvncshhd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtnvuvpmug.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtqoudusgk.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtbfvqmjgi.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtfjswuhhu.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtpoovyyri.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtwppgxuei.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtilauslce.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtwhazbkgs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvqgdshex.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtgeshwjax.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtusebknig.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtvwhowlia.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtvdokwesb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtfdtlwoss.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtpdtzriqn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtkdwhnrhh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtknmrbxgn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtmjxdpvvn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtbafhzyjq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtaoyuldte.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtybiqgfgq.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtattkhytw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtgyfpgdes.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtwghzcicf.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtqmnuscxr.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtfvbtivpx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtticiqisl.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtizguivgb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gtthsabnur.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtnshpowfk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtxyuwubix.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gthwuruklh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtoehhvcwh.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtgoivdiqa.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtcihsroij.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtvmvlwiwm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbifvhln.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtacmkvqsi.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gtkevgxafj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gticofhain.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtrkjlirgq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gtkeobwovx.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtlcqmywxn.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtkowymtoy.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtshktnyjk.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtrbcqfoea.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtzurarxgn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkabdwhlu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtbpflowcv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtpbmwkinc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtvqrqqivk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtgawfebzh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtrvalbmgf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtmvospqcq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtcpfxubez.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtifdjusww.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gteiejyfew.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtfdshgzus.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtymmsmxhg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gteqdzfnqw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtzhiyzpsm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmvusqved.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtegfffgxt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtnxtzqqvk.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtqnxmnybx.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtokucxlcj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtnsotafqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtfofcgzls.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtfckohjcu.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtvvugsefy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtkgqqjhum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtjnrketat.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtowownrjx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtwctnbrgn.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gttlffnckx.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtmcjnvyrm.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtbfriurga.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtgfmveamp.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtdhftkprn.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtzzctkatl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtezhyuzdl.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gthzalwhup.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtsehlyqfa.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshdgiui.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtbrpbhqsy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtavbqllel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtuvsxjkay.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtfhhmnnfa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtuutkwpkn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtyvarffgj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gteqkucipt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtvjloktpm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtrlxhvzpn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gthkrnnlpo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtyyqmnnvr.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtnynguhim.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvywjzzl.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtfbrbhjwf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtpbehsaqj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtajfnsijs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtmxuplowv.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtwhohnkjn.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzcmqec.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtcfkbefxx.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtfypqspya.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtdiriopfj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtvponyzrp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtpikhjtnb.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtrzbppboy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtxoccbxto.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtjrmiwcrf.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtlhdzsfkf.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtggpqcuws.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtswdzyvtx.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfhvatcs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtpsdgrdzw.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtjchjgqqg.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtodrppuzg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtvigybumd.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtfcbssxxi.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtcnyxnezy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtzqmnkrxn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtvabuhibe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtlnjfopne.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcwkdcbss.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtjygmorpj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gttbhwywei.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtgzyibbaf.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehhuukyt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtbgauualc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtuawudhdk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtruzoemgo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gttpszntni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gtgcrsxiyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtsacsxcdb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtwykcgtcl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtezjbuopr.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtlhiljumo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkidkmzve.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtjdwgyinx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgpdnhgap.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtgljfewrq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtphonaquh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtrpymzjvy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkgajvpbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtfseypkfi.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtbffdofpk.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtuckehnat.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtnbrninuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtfoffhjtn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gttypsdlka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtrxkidvje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtitwacusq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtezfhuwpo.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtvakwxram.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtbrhpopjr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtmoczmxvf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtdnlwuyib.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gthdatbabk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlfclqac.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtkodfvrnu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabhqasla.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtsdjgptiw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevnmnvco.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtyxfiqwgc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gtwvvmzvja.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtmnjtwlgx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtlsalazkp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtohgfrmtm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtqexquanl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gtelkopzmr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtlsjootbj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtpbrksgey.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtczxoacdl.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtakihrfwz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtekfavcxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtilipbygn.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtgujkkagf.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtsazucizb.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gtcjhhpbbe.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtckhnoubj.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtnjghhcwf.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtptyhyahp.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtopzxeufl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gthlycwfrt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpkufqmb.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtzzzjfsxp.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtduxxjauu.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtxpljqcqy.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gteijaidfl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gthvstmhmk.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtkiezgdrm.html


<!-- 参考信息 -->