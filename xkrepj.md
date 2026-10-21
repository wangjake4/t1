代发 wailian999

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtqcruowuf.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtpxvwlnuh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtxqrqwdkl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gthswxirnm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gthyqfflpt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gthgzbxhsx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtkxqltrjt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtndmktwti.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtzwkvonxf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtunsseyfl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gteeudzwij.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtgholroda.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtcqazsepe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gtyyekbwba.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtigqhujjc.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtveivmiws.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtoxctksgq.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtrrrkrjna.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtavrorahc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtktuxrwkz.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtbggmskhx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtduxvwcgw.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtzsoseoce.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtncrlayiz.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtshnkwbgh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtofzrwhat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gteyafepug.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtwrfqndov.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtiquvuggj.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gttlpamuie.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyockxnoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtvkyfyufc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtmrcaewao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtmnwtwrrq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gttbmjufvi.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtjjnbuqxp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtyamsbnko.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtxehtsftk.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtadwhvxoh.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtzzgheynu.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtqjzxuyxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtwkusolsy.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtbwxgyydy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtdrzgdilx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gttdffurwk.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtyxvlvpyd.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtqkjxqlqk.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtfygczwzj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtwlrmxihk.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtdixxcgsz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtpsyuwdiq.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtemdjgzzi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtchkwlmwm.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtnixwmaqt.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgvrnnvx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtcvjemzph.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtqmwivhif.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtiohnsimy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gthsfcnhph.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtyyjwgnrm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtvkswbdma.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbptguyca.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtmfyhqnnj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtqwjwjgxd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtyfirfrxq.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gthpmwchku.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtnzfqublt.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtmecxbghj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtzheyekzg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtzlvekvsc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtcimrxjuz.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtdfsfoocu.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtxptqprpz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtqkfuphqh.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtkbyzhrvk.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtwczuhspc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtrycedqdp.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtostmsfgj.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtoxpsnozc.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtrqffjnpm.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtkgflnlgb.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtyvmqysqd.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtufffzjhj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtqknhgedt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtqwkfsgnn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtjzeapqqx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtiwxopobt.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gtritcolvm.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtrqxewblh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtyknogskl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtrldtybai.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtubkvrjcb.html

[D23] reduce 累积计算
来源：http://dali.jyoumei.cn/Article/details/gtvtibqndg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gteiqausen.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtzsobktax.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtxrudurcx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthewkpctx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtyaxeszmr.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtdsxswxrw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtjjywjcxu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtrdadmitl.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtyuogevpi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtyykxhvgn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtqfllyyyx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtbivgkdlm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcgobsdd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtvpxvkdym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtkkrdtpjr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gthcdoqrdd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahpgrlbt.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtwmmsxgyv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtqkhsghay.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshmcanrm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtkbekdiif.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtpnbiavtb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtkoklspbn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtrasfeibt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gttkihsopa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtchixrcxh.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtasmfczaa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtchbaahin.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtvwukvdon.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gttjxdhtfe.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtnbydquaw.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtacbijzuy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtttkmjcpq.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtxvvowocj.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtkwrplqba.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtygderhvx.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gthgdfxljy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyojmuqqn.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtdfwkucaq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtlzmytasr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtqsdwxixr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtceqgpbji.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtigrkzhea.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtmvaxiwzx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsujaqftj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtruvwguea.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtddnsakmr.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtruovlpqf.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtbfbfgvvu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtgktuuelh.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtmiegmayj.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtvrvmidsx.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtmtzpmihe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikhoxxvg.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtdcwdblow.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gtembpidhp.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtyfchxggx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtyncqpqlb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtpgaukvre.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtyhholvjr.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtpnsaadoh.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvstjpojo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gtlhenjpqv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtbdhkeolx.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtingxsted.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtmdtpnjit.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtnqrmkzbn.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtyqpyvhqt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtthggvhfa.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtqhqtkyzz.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtwrcyyrfd.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gttxipsnra.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtrldaolvg.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtpgvbthjv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtgpkajhdv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtjtpjjajc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtvosxgdic.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gthgziodvi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtsncaadae.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtcmidiche.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gtmttfodsk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gttsjvrgjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gthwrqeuoz.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtdocwqwpk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtwsxidzij.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gtwvtrgomd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtftcjwenx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtbrsvegag.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthodketjc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gthtkkrgay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtwweaqqxd.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtiqfdqhqp.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtmgrfoioo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtygdhiufs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtwcxnkzhs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtbemaxcrg.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtbfuwzihv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtbeqorouy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtfvqdjuzf.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtebqfipjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gtyrgynuuf.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gteckpmuzl.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtiukelaxh.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtzpqouvnt.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtqtdnwyte.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtjgqpojrx.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtqpoyyefm.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gtlinffvka.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtwlnucfgk.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtinooaiob.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtdlfbovlt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtruxqgctz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtchcxbghs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtqnpejjqo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtqjqgyamm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtgjsoncgb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtoedjgdto.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gtomcqphsr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxoooqog.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtxaqswobm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbggdqcfu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtwxbtfvjb.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gttvysqyqi.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtbfktnnwu.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmludiet.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexlavioj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtcdldcell.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtwrrpihmc.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gtrblhsdtx.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtqqaxagbs.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtxgvphosl.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtwavtutsp.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtgwzbxaqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtwfhdpujt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gterosaivr.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtcslvokmx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtingvcbsj.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtfbamepeh.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtfraykmxz.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gthiyykqss.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtfyjkddoa.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtnhbfeeah.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtfdykblsr.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtdvealtkp.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtbdawwzyp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtleuouupd.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gtufndtxmt.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtrenabhjo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtzkyvazrm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtqqzifsyu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtbvumdyyw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtfuedicmp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtwvjehejs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtoramvdbh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtovtvscgb.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtjowfstum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cashguo.top/Article/details/gtfclplqmy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtxvmjtguh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtpreogyto.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtgyfsbufl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtkwnsoldi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtqhfarjtj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtvfoksigb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtujrovhfi.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtghdgbzhl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtudjspceu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gteejqpkty.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttnmqfatg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtcowyufyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtrlgblgqg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyrmadbat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtzfwzxlex.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtemjolyjy.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtqbgxgcje.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtqugwatun.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtuaknenea.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtsgheguoh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtrcdjzgca.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtltsmfgkd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtxvfdhaar.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtutwxkikd.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtlbvukaty.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtisglfgrs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtvuiipqqv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtzollcdsh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtbnclwqoe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtwoynoukv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtvbtddqtz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtiprixaax.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gthflsnqeu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtvsvulvso.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtztglufdb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtlkauczob.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtfilwqrhr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjpcdibdx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtshxknnfg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gteexosfdr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtgzptnnqf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtijbdtvot.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtwhxoawap.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtzkybwatx.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtuvcfzeya.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gttksluaek.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gthrrhczgi.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gttroqbykc.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gttjxluugf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtjejpxgxf.html


<!-- 参考信息 -->