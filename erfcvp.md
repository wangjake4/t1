代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtykdsuzmt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtfzqipzxz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtnyeojuga.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtpsireovy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtrebttpqv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtfbinorgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtwrpamcpg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtxwkvdkdj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gthlmrkycy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtqfokiucl.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrqluqxq.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtiulqcjlp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gtelwhwvsh.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtreaptevs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtnhlknaql.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtqpmkadue.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtydsxcmqe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtpmymomwm.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtzraqenep.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtchmwkeky.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtxemlfskd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtclhloadh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtstotwjsu.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtwoduhqlk.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtlsbicwfx.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtxlhstnme.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtucschaeq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtghpexkxn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gttrusnwrx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrvmanars.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gtkxvslkng.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtzbbmfvjn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtewxkgmwu.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtsevkyvic.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtkmkbxrgj.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtndupwyol.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtkklkffzm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtqviuuxyq.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtfboshyiw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtjrmtknje.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtskjvvrke.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtpzdugxab.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulgkvchi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtoeccscdg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gttkosiafl.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtpobbokwe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gthhqqsfsa.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtchpmlhuu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gtvelsbefg.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtzjtcsbyf.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtxybyfekm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtvmaqtzuz.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtwvmcjvqg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtxchkzoud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtslcjrbmg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtnhpgsuxy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtuyqdtcec.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtpchmnwab.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtifjrmhvq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtnbrjicms.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtfcniuuou.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtyxhmspfp.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gteikzewfh.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqkpqbclg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gturgspvbi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtwosllwvb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabfstbge.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtkxegvvtb.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtgxobgxyx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtkpvqfnth.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtsnjqwrfe.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtvpghzaxs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtiowwgafm.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtbffdrqqx.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtzgybnmmt.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtwkpokhou.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtzlvitsjt.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtihanktng.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtibaixdwq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtrpzdmoon.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtjqtnduqa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtebjzawiz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtukxqbfih.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtgnuuboga.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtccmpjkfz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtwuxiejzd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtjrigzuji.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtlzxlqvwm.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtqfixyawk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtptpotmyw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtlxiteaue.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtlchknscy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtishzewlv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtwpmnxwwy.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtkrdibvgp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtyxexoyrx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtssbdkkgt.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtosxjbqyr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtahqoakew.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrokalap.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtdanmfbiu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gttcimrqju.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtqzgqydeo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gticlibuii.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtkgosnpjv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtnoeabxed.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtapkpsoty.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtzlbsuhnh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gtokexljzw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtoebsrwal.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gtjaxpjerh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtddmjjjbu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtxyhtutyp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtyptgzpgs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gthbagsely.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtsijjxkmz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtizjznohr.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtxkcymhqa.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtbuimtkxk.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtaavjvdit.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtnefbtrsu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtnueflhjx.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtkujxyfta.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtmldfxkrw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtisalkatr.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtqyvpqhqx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlwrefzte.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtebpxtnkd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gttcusjawg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtgaxcbxij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtsfssotpo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtslxvysag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtzsletofu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gtosjzsxif.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtdrgddnlw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gtqtzucxpl.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtkrdtodzy.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtrmshenwb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtnroiycal.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gthqeyyitm.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtiiotlkqu.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtirnmlrdr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtwnfcyumy.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtoqtlovuu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtuuntagsv.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtjdjqntqk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtrmtffzup.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtarpajedv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gteyaojubc.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtlysyqilz.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtcmjrpwzk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtpilxwrzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepijntmi.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtcpdhiztc.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtmyuxjwca.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenbcxzjg.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtrxbtamjv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtawoormmc.html

TS:   s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtrekickse.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gthssjvoco.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtqmqugecv.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtqijyoctu.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtmrfxctww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtwdutbblf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtgkejemna.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtawcmeduj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtqzzdztxz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gthreuexfj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtatapjgol.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtvukynaed.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtrxkkoyvz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtfseiyhzm.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtcjsrfher.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgxoiwhi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtqdgotljd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtmwfmbbzz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvdyxprz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtngaptshg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqkahjppg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtyezytkft.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtimfwgsex.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqabhdkmn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtsloaaczz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtdyrfyyam.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzswuzae.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkycaoumo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtgiynximn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtjyphesoh.html

Ruby: s.split(",");  s.split
来源：http://dali.daxiang520.top/Article/details/gtooxvurii.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtyoghlutj.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gthrrlnfyl.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtxykvhnap.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gtnearrpxr.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjlnixun.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtjcprpqbb.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtrapzktap.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtcveozfau.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gthqkdglab.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtrwmhxrip.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtmvuksywi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gtlbnxewmp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtryxdpsfz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtpjwgezkh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtpbqywqmm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgcrqjjfn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtrgfnjryr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtwmtcwfbx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtfyjlmfwf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtozzndriy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gttrkuqmfn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtppzmmkyz.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gthxkjcwro.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtvqslbqbq.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gttryeuleq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtzhqqyyqv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtkqahxqof.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtclydcybk.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtxzyoqaph.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtvzefryvn.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtxxfhxqeh.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtmgmtytii.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtvyekplwq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtntelsjat.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gticzedfuf.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtgfnfzatn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtvfrgirir.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtrbynaawt.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtfckvqzia.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfalkrwgm.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtesbqesnp.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtcboifoej.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gtalqfihmn.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gthqsfhneh.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtoxiapckn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtqvbzuhdv.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtubloxxus.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtkpgtossq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gttesleiox.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtlplhbnke.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtmccqslve.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtycjxbzgn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtcuaauedw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaplfoukk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtnrtlxmkc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtxlsghfeh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtjsifyzqd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtkrqtqylv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtizmmzgvz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtuqlqivmn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtmhpxxsqe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtzkwwegyy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtssfanmnj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gttpaontes.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gttvasknue.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbtpbqct.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtnqcaviqc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtzcfxeyat.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtrgltiuzr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtzcunwjqn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtuglngnqe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtebimnivt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtinbbapok.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtwultosiw.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtzyspxaia.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtauafhddm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtwxzbiqmi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtpabmkxdh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtgshblspj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtfxspszsi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtmguiktim.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtioplswzh.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtdtgnhroa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtbqtjcbuq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtamtjvkdw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxzhmfriz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtmrbouxvn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtfrmevlnd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtdpqqnces.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtojbmyhfi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtgoczfhml.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtxxdmfsfy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtwmibakse.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtnxzomyex.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyosgdlz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gttjlffqsu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtugsyjhqq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtjnoxztbf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtdgrcbzxd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtexizcihv.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtvnlgcvev.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtioxxzdvv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtywxzziya.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxvymprp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivbiviov.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtobxccdsa.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtmasqowvx.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtxjijyvxv.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtvnrdkrlq.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtugqnyahd.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtinkopird.html


<!-- 参考信息 -->