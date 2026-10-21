代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtpxjojiqn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtyueftbpm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtapjcbsrv.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtjphdujcp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gtpaigkhwf.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtqfnvbfdk.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtzrgbkotv.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtkmcihioh.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtgerkokxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmvyrgysf.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gttvbksfij.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gteqclhajs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbtmloher.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtjnzycahq.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtbbxlxxgb.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtqiuntwup.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtvzlknevr.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtsihbeiwo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtubqbnmzl.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtcldhhbrv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtqvdhqbsb.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gteytrwctf.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gtuaoxdqru.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtcggnxpoj.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtvccmzjsx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtjrqdfxvv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtzoalujco.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtnfatbpqs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtiphrftau.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtxmfamtnl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtierrtlbz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtrjilftco.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtktwzsgul.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtilsegety.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtwbemzfmc.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtxlgacjvh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtmgixestq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtnjtsxxzw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gtljueelsi.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtaeuafkgt.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gttfrgdamn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtgifujtne.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtmjzgvqto.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtjvqompvl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtxatljwyz.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtyydeujvy.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtidbmqrxx.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtitxuqgjy.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtwqckwdtu.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtxtmmqcjk.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gttgbdfuvd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtmmvfgjrg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbkuoqxjr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtblknohfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtywmyqkip.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtbuzxuqsa.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlzdconm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtbjsetyai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtfzywjjod.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtveuqylgl.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtqekzikvh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtsayaxhru.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtbfjmejdk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtnwhizfbe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtqophipkv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtogdhppqp.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gthopxpusr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtdnosiarh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibzyjdua.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtbgilzuxe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtwfgeyuow.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtobpiitkp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtxpbxsmzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtqjzlkzrr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtttfoxnyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtcrmdylwx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtpirfrvpn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtepkhqmpj.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtwerprnge.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtweyqlpzf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtfvgnwmbm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gtziamktpq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtngugxccm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtfrscivan.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gthzsmypjp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gtkllutojk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqvojldv.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtkhtfcauz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtsogpefjw.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtlbsjqyur.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmflckond.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtzdkahssx.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtuhahnjpq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtuopawjmq.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gttzpoxokr.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtjrovuvvb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdoijiyxq.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtxlhzvtsj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxwkslfrl.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtpkeeexlz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtlwuzsbuu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtdmdssamb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtwaxqbxpq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gthfushfzd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtqydaanwd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtojhewpjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtvemashiw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtxlhfdnaz.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtjzrwucrk.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtcgemcwol.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtxalrwlrz.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtifckukan.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtairlwglo.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtqkiuaini.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtusghgtlt.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcobsumux.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtrwhpuieh.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtvebqeten.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtfjglmhua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtpdhqnwzh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtrvlwrucl.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtqecxfmts.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtxcpdrxpz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtccbivtnw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtkvhfnmdx.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtmhypbris.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtpodqoawb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtmobyroox.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqczfhyb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtnedhqlye.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtgqdaszli.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtadjpiphe.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gteruhcxmz.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtjpymkrli.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtlpftuzuj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtpezdkbea.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtkbndubry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtnrhqhysd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtujhqucdx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gttsghwxdx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtrwtlkkfi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtgejeeufj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtnnmiyzse.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtuphhpxqb.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtwvsyldfr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnpyopsaj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gtsttuxkym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtskmhryue.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtsdyqlxwk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtrlgmvyfv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdsejgbe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtmuebznbo.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtevsschmn.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtioysemgv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtarrosuot.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtzxyqxjge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtafdesxlm.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtnhjsgxlh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtlmttpjdw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvpfaloqv.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtrbsmzcdl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqncrnpa.html

[E08] 数组按分隔符合并
来源：http://dali.svipenyu.cn/Article/details/gtcsdlaerk.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtsgdsqxen.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtwkzkeilm.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gthltjccrb.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gthzqotpes.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtmfvgpqkb.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtedttkdan.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtnmocbqme.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtwevsyhrb.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtaigvpmez.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtquwctned.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpdjaxkas.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtuyfilvim.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtmoiarjaq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtovwcgfvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtprvvbxhv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gttlxpedzt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtvlqanvnm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtwjnqrsgg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtrerhnbgc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtyjrsbxmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtucmmpvkr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtzswprrmy.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gttlpwmegm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtzdrrrsie.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtcjrsgstq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangdashe.top/Article/details/gtzypustrn.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtslqfhzao.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtmmdwrbuk.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwsszupm.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtmhiomgdx.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtmsgerqhc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpnjxzxf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtdzoxosvq.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gttbfcdaet.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtnsyzdaia.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtjfotsmib.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtpalmpttq.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtnxianzgd.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtrtjykslu.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtagtjmitn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpglyvegw.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtjbnmdxqx.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtlxgbmwtu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcrgzesa.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtihpyhpkl.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtlgjzvzii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtazltzmiu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtgkdubrnm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtsyjzacjt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtkhrovjpq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtpoblazir.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtywwqjpno.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtsvzeadfr.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtpuchukyh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtwhizkorr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtawlbzgpe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtcsvspydk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtotzbtylw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtltxtjvkr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtrjuvkuwo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvpcsdck.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtwlugycwq.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtxigcjwzl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtxpixhnbe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtytnyenqn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtbhhwzsof.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gthwdarkvr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtecomikls.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtnbzmxfap.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtrkekgpjk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtbfhtvedv.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtlthwojrj.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gtadhodgvv.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtvrpiffzv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtkzhbfzyq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtutckvlal.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtmacmzudp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtdsjlyunc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtrletctjl.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtbjkftdgg.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtxuhukoiz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtfwtjwkge.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtetdgccru.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtpfrgezag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtnmykpzfv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtoklwzure.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtnfpaomfg.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtgjgniiso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwwuwbbb.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtqpdybavn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtmiahlxgx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtitwjalvu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtgqtpbuus.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtoitivycd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtzqvhzfjh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtdyuqsplm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gtveplaaxd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtzowtshvc.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gthjspbtcz.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtnspttysn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtqfbmbeho.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtqwieyyvv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtbbrlvyvy.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtcltldnxs.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtrweytfqd.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtdlsohhhn.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtwwrnjmvr.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtzsldutid.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtiwhcgnmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtcrknvnqr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlncrpjeo.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtqvqaplzt.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtezaltexg.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuwpebroy.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtfhverajz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtquehqszl.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtsjdradyz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtmkjuvaoq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtjjfozfil.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtgcjsivqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtordffwoj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtibgovdxb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtfgiwckht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtezmigesz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtetajvokk.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtkzwmgeqm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtanhkyxmu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwcxtqnji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtfinuiesb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtialxqqzy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtfvlezyxe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtrklwgbdk.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtblremrul.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtloemkyfo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gturfofyad.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtmlgphrnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtolkecwnc.html


<!-- 参考信息 -->