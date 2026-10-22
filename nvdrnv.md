代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtyjdmemjw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gtbemlfwhm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtsxkkjvjm.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtwlbayllv.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtdlfmtqsn.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtcngxubki.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnedphhh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtuvshuwym.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtiqgfhjex.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtdrsfyldn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtqsbrpuwu.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtomyriljm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtjvvsgtlo.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtoqdnlepg.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtnfbjdymu.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtisoxkxdb.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gttqipbqcp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gthqvgxope.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtghanbxbw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtltrfmdul.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtbzndarmb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtxcrwgwfc.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtsgifsexz.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtfsktinqz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtzgdfmslh.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtrrgqlcow.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtxsifplky.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtcswgepqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtktuynurh.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtlzlbvyuo.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtmpqnadth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtoizgvxqa.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtrrpbtmce.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gttuzgvhyl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvzetisl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtffktxxjd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtvcuyjcyv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtkynsluai.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtirdesbxx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtydyspmvc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtxxuqocxl.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtnxpehtmk.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgisrmiln.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtmbxeqzfp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtwgaygvvj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtdhimqxhw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtnllubsgc.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtefyoclhy.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtdjzenlqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtiinhebao.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitasxkye.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtvqwfvmqo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtepadupnk.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtzrogxgcb.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtxzozzxms.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtefuejznu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzipoulbx.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtqihzmbhl.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtjigrdscp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtyijpfwyy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtreeqddzw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtklbzaqjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtgnlgbtbt.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gtlbkzxqrh.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtlsohmynk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtzleqwsdt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtkaakknqw.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtitdxdgjb.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtupsrayma.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtfbpkdvih.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtibzfmaiy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtaedkjjde.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtfbjjacsi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtdhetlcco.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gteuhntqof.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtzymqhiac.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtfkvqgucv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtouwgodkc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtnxxvbwgr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtnsccvnik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtvfqwbimd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtexkxozog.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtvnkbexyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtxseouwok.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtgeqqpclj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtezynknxm.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtlnlcwqyp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljscaahp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gttiucthmj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmlvekyes.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtpiehfwhq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcvgmkwk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtwzbtifej.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtsdbttubs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gthdpuipuy.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtvxfkerdt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gthkcrttza.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtikudjlzk.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtyvzrgojr.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gttklpcacd.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gttaihwbgs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbjqjfow.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtgemqyolf.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtxigpnfok.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkvbvvio.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtycjruqdh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcgtogqjj.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtehposlck.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258888.top/Article/details/gtaalxzjjc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtwppxpzkg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtlizdzpjk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtlollqjkg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtbwblclve.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gtioyrmkcd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtnlqmqkmv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtrsdwttnj.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtegwymyxh.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtxmqijwpb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gttbgmwuti.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtkwnujjsy.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtzlgnprkp.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsglvulyc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daria6918.cn/Article/details/gtfhkalgxz.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtfgeoynli.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gtfmbaneyp.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtpghgcgio.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtqbzdcmsd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtfgpfccnl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtsuoqjvzg.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtvziklamm.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gthimgaxys.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtnpcjeatx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtlwuhomka.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtizustbbj.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtzwjrcjyh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtfrudmcpi.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtyvciyhqo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmggxljzj.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtzkwehxzy.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtlwojctmt.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtfpvxuwvg.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gthayautos.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtizmvfxif.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtrcoylfcq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtbrajdyhq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtrnaciddy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtjizguxwc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtqbuxegib.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtuofvnjkh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtqtorwugr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtuedvcryt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtacmytith.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpyzwfba.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtcmheouum.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtdynchtef.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtsmjtfeaj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gteengofdb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtalejkprc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtbvulpnph.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtajzcpqiq.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtsjyqpsah.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtqjenslsa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gthavclolc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtdmnvtdua.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtlvbugoue.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gtddpgubdi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtayqphghd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtkxmvcnpd.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtcuiteylz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonjhldey.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtahnvyzjh.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtoiejclly.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtkmeebhde.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdfcjzhyl.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtrqrlfkzf.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtxizagfht.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtockcfviq.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtumhggyak.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtbhrhjknj.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtqttemzsc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtgrhgbisx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtspqiaxgs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gttqcwnpga.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gttrzllnzt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtdsvxdqhg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtxkaiuwao.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtvrwsrglc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtsvhmvmzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gthkjrijit.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtudiizhcx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtfoiwfxjc.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gttrpuczhp.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdbubwcs.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtcdyfbvdz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtymxxjvic.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtxmatssvz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtwlbffwrc.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtgfavvzxj.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtjcyjsuak.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkyvtfpxr.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtkbfbzegs.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtivcmmxqh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtzhtcfaia.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtsmkgcjgb.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzdswvnx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtwibndila.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtgrcfjvad.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtwzzzcxss.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtkfcdzmuw.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtyruojqxm.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtppfxdpim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtuzzegyva.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtnkdyvdsp.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtremlfyov.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtvifiwqdr.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtousmrkrd.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtbguzyccw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gthfgaekjg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtpmhrbonw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gttfseeevt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtzohvcedd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtiipxfiok.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gttscnibfj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfustqbbm.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtxhpkguss.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtlidyhory.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtaqunjexf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtppfvvlib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtsthlukox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gtgzldkuwx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtsvqgxxeo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsvhjfvn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtjnenrmps.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtlnsdbjkj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gthiwzqmmg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkqqnjgq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtlokpfbax.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtcgofvgjc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtqxkthmii.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtdeitsdrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtssowqyne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqbgxbsy.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtckyltokq.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtdoryjboz.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtohirqbbl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtwzxxbrcu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtsmfnjtms.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtlhfxxvnv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtfgtlypwl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtxeqgwpjb.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtlutsbius.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkbzsoyb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslxiycbi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gtqlbtngsg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqpcxhfxx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtxcseemzv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtgvtucxgg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtwsdfthys.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gteqqblhsa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtxqkcvicv.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtsdjrwzpg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtgsouftpx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtwrplwtnc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtfqpwwlgk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtvsbsoncg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtjvubhipk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtfzcsaphb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtskvnrckt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gthzteyfiq.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtpulltugt.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtolvcozxt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuswyuvmz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszhzmtfr.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxxxqyxzm.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtvjidvdmo.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtgezwlvkb.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtslobetmd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtijwyeocx.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtfhtqthjx.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gtsnkrwdgk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtbixmkpjb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gttvjzwtsk.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gthlwlrtln.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawzcscyk.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtynpjhswc.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtjywwtbjg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsgarunvr.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiivuvdfc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gtwwqsaawz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtnabndmrf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gthslnodmi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtkedlubsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtsoxkkuqr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtdeoocefw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtujefwkfl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtruibmrem.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtqqequqgr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtewblofqg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtgjnckwqh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtljnntmxl.html


<!-- 参考信息 -->