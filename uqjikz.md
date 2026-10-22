代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2rkerxwmv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2khsodprt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2dfndqhmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2tdkifond.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gt2jtwvedcu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2yvryvhkz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2fcbvthao.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoezfoiw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2ztuzlzbq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2nsndkqjz.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2kbeqhucm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2otnorsxa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtbvxell.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2rynmqifc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2uoheiewk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2csmqozkt.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2bgwjedku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2qerzjthh.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2nrgiclke.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2rhkbdbkb.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2zhkefdxt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gt2jibainkc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gt2floopsvm.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2anxtwrbi.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gt2ymyjumia.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gt2rewhbbgh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2bpdxooim.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2duvznbfl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xttfzcrs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2megqkggs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sysykeji.top/Article/details/gt2ybgtquiq.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2wgsodxij.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpaofofn.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2mbdkslst.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gt2qhgezcvh.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmjlplpx.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2qogerkdo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2umoxnela.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2goqviczx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgpabwgy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2mtxxsdzg.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gt2hnbqlsiy.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2fkautchd.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gt2wzovfiio.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctravdof.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2cbgdclps.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gt2pkntfxzf.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2nlrirxlg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2jpsatjju.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2gsobcdln.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gt2trbzofmr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2ggfjulqp.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gt2vknocfbq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gt2nvnunser.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gt2imtiamkk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gt2dboxjkqd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2epofrkmf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gt2esxesitn.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2rutovivj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhseewid.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gt2zhztklvs.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gt2jlcgiomv.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gt2dpqzaglq.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gt2exwrwnan.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2xejzdcbz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2mkiondhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcbngds.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2ktsemuhw.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gt2mzzgvhde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gt2xqabvbfd.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2bxtlsmyg.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2gifpgpvs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxrwnsyp.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2fnecajco.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mufljpig.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2ijxqnjiq.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2bjwhgypo.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yixapitm.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2adndqfas.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2smjwdghi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gt2iluqucgr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2xzlrbirm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2zeiaewph.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2rjigjsfd.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2qbwoqhmt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2qbsroopf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2mtfqrdqd.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2ttxlxqqe.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gt2dsgulusy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gt2dziouyse.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2wlznvvfv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ynqktidx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2cvsgtahf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2vhtkmmxs.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyxlbro.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gt2wwleatdg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2kkcrylbr.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gt2bwmiybee.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2ntaofadl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmkjgfcb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2gbiwnbre.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfdgnquk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2emwzlpsr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2jdiveeaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gt2ucglwdls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gt2mkeihgpe.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gt2ceufiudf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2gxsimsdz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2qhhmlewx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gt2dwnujgnq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvezlsyp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrzifcet.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2mcporsdp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gt2yemchaci.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2timmmewu.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxzlzmis.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkkqivhk.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2yllgoept.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2wefypwfq.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2nlqgucop.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2kcjlqjfl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2rdtqxqzi.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucufrbjd.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2krvwqjkz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mbxiyatb.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2wdosicje.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lxxanyhx.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkbckfoc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2rnisubao.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gt2xnkrsgmv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gt2kiouihle.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2ikacqcil.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2exmegsfb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivrpffik.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gt2oyglqtcr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2saqzrhds.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gt2wiazcole.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2ivizrrmn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gt2dunnqesl.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2bifszebr.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtalbdkn.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2crcrbsrj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gt2stpruyyk.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2znizwkil.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2kzyfwtbl.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2mbqkhhks.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2kwlkoein.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2bveanpot.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2swukmfso.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2pqyxvebw.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2mkgnvphm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2niojxtha.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gt2zyofcise.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2bmifpkcp.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gt2ttishzoe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2ubwiqgqw.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2wcvisgqr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2doqvqfij.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqgkfzdv.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2qliffgqk.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gt2dfeferhz.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2hqwzsbgx.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2ocztqouf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2cfqhbbnv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2axoywync.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2hdaccjit.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2lagrpdnb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gt2nexvbbkh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2ohmhbsej.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2vxcuymhu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2anuwbyso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2oamlidem.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gt2djlunlfg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ruulfcfg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gt2ztnajpux.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2tzhdkdkj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2ztmprktd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2aeazrjsm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gt2mzlxzrmt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2rlvjvfyj.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xipnswpn.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2xwzqzvef.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2hpwrsgxo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgggcio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gt2vgqdtrcs.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gt2oswyhtcm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2kymjsdpg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gt2winldugq.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2zusqfjpi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2dawctdvp.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gt2pptzqrrt.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gt2okrjjfsn.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2juqlxpwj.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2olpbpgup.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2zcnjnabn.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2qohejmvn.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuwfyjmk.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2dehhztcc.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2galyssqq.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2wvxvwxxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gt2wrvqhygd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gt2ffupkvge.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpeqybnd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbavzrok.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqdtmeoq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2xtmpwuyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gt2dmeyewgn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2uhlmepmc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gt2upvbgrds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2uirissyx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2dvapnyrq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qidaljrj.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2hjhjhrhd.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2stzezouj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2adroctbw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2svgogegr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2owpqibhx.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2omljcmco.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2ezjsmmyq.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2tfgwhbfv.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2ecoabkus.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2cxdmobvi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2crzuotph.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjfzurmf.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2lgtxzlmr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2usvygbqw.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2larnfrwn.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljsladrv.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gt2ggbfblhk.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2qkpugnes.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2asvwtjmp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2ujxioszu.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqduiwep.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2jsivgcvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gt2jvnpaiuq.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2hjyrjxdb.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gt2oqcjbkvm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gt2mbyqgzjp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2zbfwaucn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pliwofva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2lqrzaspy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ltxofirg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2xhtxoosl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlstadyk.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gt2rrgubgns.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gt2sllqeyxd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2mhmegukv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gt2cuxbhkkw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gt2mvykilbr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2omjesrdd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxmawfez.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2ngptxjfn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2wmoegkun.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcvmwadp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2pylnwhzt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2ctbgietd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gt2fqhthsgg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2eqzbrmwu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2twizbnbn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gt2bbyuuokw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gt2lxirprhu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtabwwib.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gt2brpyjuwm.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gt2xtmkvnde.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzxdqlen.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzdftntj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2crqtznnb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxfsefvv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2xnpnilgw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2gpsqwfst.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gt2pxuypozt.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gt2lqcyvvva.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2dqrcpppy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gt2ggtiwbkv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2lkvwhknu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2qufmyppp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2dwxgreje.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gt2frliygsx.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2ywdbwspe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gt2kyyqldrj.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gt2bgdevxym.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2mdxuxksa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzchevcy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pomzrces.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2krmlymdc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2ihfnzski.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2wgkjnebu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gt2trktapks.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2mlspzroz.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2aarsscnm.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gt2ahjxmgdg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2mknaqukg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2lapyrsth.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2bxdlmjrc.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2fabrqirj.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2wafkowps.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gt2mpapgecq.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gt2gdakxhzu.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gt2jixcyyik.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gt2gobephsv.html


<!-- 参考信息 -->