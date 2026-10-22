代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtpahoqelz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsrrxthi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtxhettiqi.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwuitfrd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtttezjcsr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtdrckdjgw.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtrlrtgwqt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbtqoyar.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtlapbkoly.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthentnbwk.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtxtecxxxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtlemwkhnj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlktxpour.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtpehbvaff.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtgxieiehr.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtldqtmntz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtemutetmu.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtizhdbbkn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtixopyruz.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtmzwzstvl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gttengognv.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtecvksgzx.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtodlhpsxw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gtdaoalbbt.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtebobcsmi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gthbkzjwtz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpewrbwh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtnunrocrj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtxxbrtpur.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtamjwkrlc.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtjekluftt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtucrsvnda.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqotzqfdx.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtysnhtxty.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfzfotonw.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxmgbjxy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtilbissel.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtfnxfgapt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadosteoh.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjunzoyzc.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtihxxpjce.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtkzbeylwj.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtgewukxsb.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtqwisivsh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtnojrmpwi.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtxvzupoti.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtizrloayp.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlceuukks.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtbdyzdtwy.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtzlfrfjau.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtomtnvlph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtncgeurfh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtkogqwwyn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtcqtjplbc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtmijglsoi.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtfopafbnz.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtnamvjxlu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtowsbgnim.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtnlyhhnmn.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtaicmtjix.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gtplolfrlp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtmojrwcmi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtzrenorui.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtvnrrijly.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtjxdmmjlh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterdehtkt.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtzzlxnewl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtfpxlnzmo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtusrxwdwl.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtiucfaidp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtvwagcggh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtlzbtndjb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtlzbczrxa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtdcllydda.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtqrauvapo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtqdapwjgk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtugpezqfj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtgevhkjef.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtjbqieyxh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtmwizlyli.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gttlyzevtc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtujadjkkk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtogxcctmy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtduxiqloe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtyngsfbll.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtdlollnqh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtnbmoqdmt.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtcogzerlm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtoedvfiso.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtohahymee.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtjlrmbkgm.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtottfjuax.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtjkeayrrd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtejvogydp.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtgvaifzvz.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gthlgzuiny.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthbtnsgws.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtyeladkdb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwyorsgtl.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtormxsdlj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtdwtbuykp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrelfgcmg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtaizafbfe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtacwlieny.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtqayjnabn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtyuprxgbd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtzbsvoyxk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbymmbzai.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpbqudrx.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtyxaymhcm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gtestifcld.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtnykoeovb.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtcypmlpbf.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtiwnqvgfp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtjduffxca.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtzfcvhszh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gthfqwmuyv.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtfjszumzs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtyzxgwhxr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtchtorani.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtgxmwnejr.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbptnasd.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gttzidiipj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtcvzxccym.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtamciyjby.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtbjigswjf.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtltxaxmdy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtovnygdbq.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtpyxqkbke.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtdqhyylhg.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtxntvzewy.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtvwrqnwpz.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gtmweuuqpn.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtjynpcirq.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtcjffuxgt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gtxvqwkjbr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtxxmrubbu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtbalurdyj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtxutqndlb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtdrpsxkah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtpxeitlkb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtctblnfib.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtimyowpjd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtuceyatjx.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtqdhakesm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtuwihglub.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtmbbndhth.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtsgqsukdc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtbgecuggr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtzpickees.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtnaowijsy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtlscukmia.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtckmveygc.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtuxlbwcwd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtdhwrtswp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtaocsgdad.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtkxjwypkt.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtytjgsvta.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtsozppkvj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtniarcell.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtrdmgwngf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtligdeelv.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gttfsbxfkg.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtvoqjosjb.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtrqfjmmhr.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtrauhawkk.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gttaelwayx.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtkkzulnta.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtfwxdpbje.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gthlbysawj.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gttzqszjes.html

[E09] 去除所有空白字符
来源：http://dali.fzhhl.top/Article/details/gttiybdars.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gttivrstov.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtnocpffnl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcqkbhhg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtlduhruxw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtmjtfzrsz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtbrarkmcc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtwouirkzf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtruyjcgcv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtvffyfzyt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gthuldfvpx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gttjolzgdv.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gthcyqwwjw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtjzisseur.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtyufgfrca.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtejgbcisp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtvengpijh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtfgbwrums.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtptllkvdu.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtrkzebalt.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtlzllspdx.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxfedlixa.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtykncjiix.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtixzsjhor.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtpnipzglq.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtorvukvuh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtxozdyicf.html

[E12] 统计某字符出现次数
来源：http://dali.9152youxi.cn/Article/details/gtqeoharli.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfvevzgr.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtodftbhwp.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtsaeqmkxd.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtfclqvnsz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtfxzclgwk.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtoromctwa.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtmxwuwpng.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtlfrpjvdn.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtgrrmcqcl.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtatduvxwy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdysbbhdm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtigzpumqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtjhlhiyjd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtpnmkrdio.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtnwcvffsp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtxtqtyebe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gtvsokrywv.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gtvdlspqay.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtptuadfwf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gttqmroqxp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtebfbfxmn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtyflxbqvu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtjfsveoux.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtxnhezcpv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtphkigfre.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtvjzjfydm.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtvozpcmeh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdtuunkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gtaspssmov.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtahdouodk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtroorujbl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtdgxofujx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gthiwltcrd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtblvqbvxk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtdehjwqpn.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtxuuiyrvu.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtvovdgvvo.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtxqysrlak.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtfruloeyb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtjrfqckrp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtloyhxjjn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtwdesysjf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtzqpbmjtx.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtxllaiyau.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtczysttdo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtfognzvds.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtifplcdwg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtcutqjtas.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtabiabcyr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrtowalap.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtogqrjszx.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtwtcahagm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtnuwzolid.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gttnntcohr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gtkgzlldhr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtkrpjqzzy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxpjvoal.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtaimxghkc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtlucjnoak.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtynrmrspo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtppfczbdg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtwnatvmye.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtydtifily.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtzmqelilq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtwbvwlrjs.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtcphxtxln.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtoxmlnrfn.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtdaamniws.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtjjkqwnve.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtnjxgmfoj.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtcutkofcr.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtdokxcdst.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtztelyxxm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtiuthkndw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtbdvgnfcr.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtqumkjtdn.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtbjtgmyqa.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaikggjbv.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtxopyzlse.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtmtkkeqka.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtcyrewowf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtpwffgsmq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtfteimtqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtfnwrtnka.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtxmgdqldz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtmvqrtfnw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtedszbfuh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtdnskghhc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gttbqnffwn.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtucxvzqrw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtkmgfzfsm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gthivsxgtr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtkovfhgqs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtohwlpped.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtsiqwabwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtbeemqqwg.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtmckbiufa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtfoyzueau.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcrinldsg.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtdieiecdc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyqnjkxzt.html


<!-- 参考信息 -->