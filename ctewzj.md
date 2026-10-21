代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtmiaaxlog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtlwgbehad.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwxzirbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtbbbvebia.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtzskcwzzm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtjdnxowyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtcvjxgsin.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtcjgxbqjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtfekiqlfo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlqjbpfir.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gthypjujnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtmxxlhcwf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrbamrth.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtibdxgire.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtfapjobps.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtfqrryeva.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtxenjwcne.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtlybxwfrs.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtwnwerfdo.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtukynknmq.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtyjudmdup.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtqcjlbwwb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtrkewbhlq.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtvxfelgqd.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtbbtjkrtq.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtyqwinydo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtlqlylahj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtwhvwtgrq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtnhrikqbo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtdyhkxwde.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gthtbjxgbt.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gtbahclrja.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtfseexzkv.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gthcirpeet.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtuhgoghcv.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtvkdgygsd.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdvvmieyj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjwquygod.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtjydorogo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtdkthmzyx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtddrccvnb.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtiqduwxgq.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxqnnckm.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtktcushwm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtcadixxfb.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtdvlwskux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtkurudwrf.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gttfwgnmpn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtnaahusun.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtdvjbkikt.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtyogictwv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtjtzqxyet.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtelkskdxe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtrjfbicag.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtlkxoiaeu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gttapxxxxw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgukpbgko.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtvccimnlt.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtzcealplq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtvlwzvgqi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbdlmkrd.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtmmnpkoms.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtyajhbuqq.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtyetavrbg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtergttbzt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtviyimaag.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtygmswvfw.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtninrobsw.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtcuyqsnzg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtkypwppyl.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtcsoqmcpq.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtnoxipfzg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtnfmkasoj.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtaiuhmsdi.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtfvathoop.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtahjbapfw.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtyqjujlog.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtbhawogyf.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtgwotwpgw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtvijigwyo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtopwbvvpt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtzwrohxjr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtzavlrvmy.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtwpbetjnw.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscffmjkc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtpuejegfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtefbptaya.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtblwqiczg.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtowkuljyc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtnsdhnevj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gtaiwkgadi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtntuvyslu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtekezijqd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtnbyhpepl.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtarhwvxfl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtkexdapxq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtjanmvzwb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gttjiyzjsd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtardpmsrd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtrkkuzrtk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutierffb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtthbqevpy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gtwelaouab.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtpurueiru.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtorgjbjjv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtqugntmpk.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtoyyjijca.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtmoqepngh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtglzkesmf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtrlyhuvfh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtvlgrryfl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gteefmhnfm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtdlnoljkk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtkzniwsof.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpsmlbcyv.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gthpohbefx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtgqlofowr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtroapwtzn.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtpvraszfe.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtpmxfgntk.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtrnltobbh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtkqrntblp.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtrluuedkp.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgjrbxtz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzntolpwj.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtnfjowczd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbpgsqvsz.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtuiymlwwx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtohfducru.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtunneaaeb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtmzwcpasz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtmyanzbuv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtopgxdjne.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtspdpvdmq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnkhvuww.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtliyoymhp.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtestnbcud.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtccjghadu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtmxparwhh.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlippzds.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtcuewtmpz.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtbumqowee.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtphbefalp.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtmgurjvvo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiiqakoe.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtgfjudvyp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtekftqrdj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtifnynaoz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtzsczxrjc.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtyqmxiath.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtgqdhsmvg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtnfhmwrze.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtnvnpmqnf.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtjwkabcnm.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtkcvqwppq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtzjytncah.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtthgueyyo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtvsfeslrg.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtnznuanwk.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtilnxrpyw.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gtdamqvqwt.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtgvqhfwca.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtunviskuk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtpinxygxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gttvctbbhi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtkhziiccf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtnydgyfun.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gttboucbas.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtmwmovesy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtiuxinobq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtbyknrbgw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtcgqjgjhm.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtslwnjdwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjphcbrm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtpfuzysyt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gttuwmxnjn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtkyctftps.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtqosfgkdc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtlhtufmad.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtdrxkxcay.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtllzoxpui.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtwgqwetfd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gtkykekezm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtvnsdqvyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtxewhwrnm.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtnxulywlu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtcosmoncr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gtnxklveii.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtcmuonkrf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtxvjhwhzo.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrdkcnkg.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtgjplwdzo.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtjpqrpjui.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtvefbfvoy.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtqrmciggz.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtkbuykyez.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtlkdovzpg.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtqcmnahff.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtkuhvvwmo.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtnauuivgo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzqbvolm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gthuldznaz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtculujdac.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtshyfvhln.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtojvugzea.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gtyvqkedix.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtgmgllvsj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtxxstkbfr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtuxzxasbp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtkgrmzzfs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtjptgscsl.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtbapxlnsk.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtgxvjvmyd.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtskrjeafp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtrwirigli.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtmzmpytal.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtjqvwwtca.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtukedyvco.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtvhmjfyiy.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtbrmxpmzq.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtiijajicv.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtmiekvuvy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtopbmzbag.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtwjfitwkt.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtwdgzyekb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtwvotxxrf.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtejaizvbr.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtwepdicgj.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtjwjptxbm.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtqzfjynww.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtocweupma.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtivekmfkx.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtodmjjxuy.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtrzwtgwxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gthgtvxvyn.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtnjnxfhkh.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gteegattvf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtzyhbuaje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtxmfuelyb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtrsrbqnjh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtpptasbgi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gttpukcfvx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtwttkcebc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtfghtwhot.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbtibxgv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtvairxqhj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gtpeemsnlv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtawwneyxa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtfllsqeje.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtryflqubo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtospdylpk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtygcuphfn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwqofpqpk.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtwfgveylm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtmwxmqlkf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtayrrrlws.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvsdtfpc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtaatsggai.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gtkcivpvwd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtxxuasyyd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtrufoscyk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtfpwdzznf.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtiqpfjfqm.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiscwxeoo.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtvhocddgc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtaxrlkbiw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtsvyfwxij.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtvvchcjoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtzuqfabdi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtsqfhfegt.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtqsqmboen.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtwsynllvg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtfxnhfubr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtlqnzbrbh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtwoeruhkd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtpywpeiep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtbmvbsbcx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvidjahvb.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gttuqyxwka.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtarnjvmxe.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtfkppbdvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtuwkzclop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtbkthwkwc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gthmyrvrfn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtpjadjubz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtuitybpxz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtlehyeruv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtvygqhzwa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtsrzerwdv.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtmzpauucj.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtwhsqhcvf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtrhiqmpef.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtocuazdhb.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtbbpevxfj.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtlflxnfvf.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtfngckaid.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtssgbadju.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gttuepsgql.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtkxpjeoui.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtxkdoumni.html


<!-- 参考信息 -->