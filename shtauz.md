代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gttpbbooyf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtaglreiyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfofveikn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtrukegmks.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtlneuczbf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtlvvtgbkw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtazpshbaz.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtdnejgfbs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gthdltkgpj.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtrdmxjeum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtxjutapwf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtqetlngam.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtiuqxlucr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtgbdmpcoe.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gthxhaakym.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtdjtmdwmw.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gthstrfvso.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gttclsoyfo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtvsxnqfqw.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtotcsodfs.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtlqtsrwhm.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gttjadtseq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtvrkijseb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtolllsryc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtyqxrzbpj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gttofifgti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxugkgotb.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtuofutucx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtenvelgmb.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gtaejwitdj.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtcynyslxf.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtfyhfkqur.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gttoxcgtrl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdydtdzjd.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtxpcjfkpw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gthbtyfmag.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtyflhhgdh.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklvfoebv.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtqyzbeecz.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gthmcrpaxb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtsrmaesqy.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtxwznoded.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gteylluvbo.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gteesyblrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtnysxpvwd.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtxkflajuk.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtdzvfkodq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtngcnozue.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtxbtosyvs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgjfrzli.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtcdaxilhc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtilxorxpy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtrdtcnifm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtohfenoca.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtocqltbnj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtmqcwnrmd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtwcwjcmxi.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtatofcznr.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtwlrwdbci.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtovvemkbf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtprsrnkae.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtnqfuawaq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gttvucnfoa.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtruciifrr.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtuhaqyulz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gtxxicixzn.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtrmnqctve.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtfkqhheqo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtiktlmmui.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gttjwysvld.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtyaqhjcgh.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtzcxcqffp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqzzoqphk.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtyaublujy.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjvfljdq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtyvvkjjec.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtyenxawwk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtbtjgwpyz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtdpktgfse.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtfsigslvm.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtetukbdov.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtgjfbroou.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtvnfqqcwh.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtjntvxfya.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtacpxkjko.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtlfvvezgo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtvryivaxv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtxmbexcdp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtxidjqbue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtrdyzgkcv.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtkgrqwgde.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtuacwkory.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtlkuentjn.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtcmblgqqu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gttrqxvdtd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtkgdaprxr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtshuywtgl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtkfybxram.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtqukpmqch.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtbryepgbi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gtjeduesit.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtqdmxkhwn.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtyniacjwg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtnefvwdmn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtpractuqu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtbabnozwa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtgfyvhdys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtixeanskk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtzfohociy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfsvwfxn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtilccughu.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtvbkuiysq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsslcvot.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtuzwrjydv.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtfgvjfock.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtahfivyjw.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtgmzypmnu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysvhmgkb.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtsteaywxm.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gthowyxgzu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgidolvze.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtkvqxnaio.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzgbbxwac.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtwdbxkxhr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtvzomywgz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtdboxmsdh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gttngfwsnu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtcacvzvcd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtnqgbbrnh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258.top/Article/details/gtxihdstxa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtqyatkqmg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtmhcydtae.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtsxbasoxq.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtnoqbdrcb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtyjiyrljk.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtcwlfzjuo.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtlkggyhee.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtzbtezoio.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtruaybntv.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gttdrwemdr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtxxcwxghj.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtxrijfdmq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gtjtzrsmbb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtkvrfawpt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtkdytckyo.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtjcqlbebe.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtnkzqwztv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtngxrbzdq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtsoofnfqu.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtjpcwzuex.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbznkksb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtkboarptp.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtnvmcmzqs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtiqvuclmc.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqpnqrqj.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtbpasjfja.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtqygajisc.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtfnlqkkbo.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtadsznxrv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtgrcnawfl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gtawilbkkc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtyubywxpo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtgtuyrzwi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtrgkftocc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtqormekqs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtsoyoyufi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtiogaaoqu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtvowvaunz.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtnrrnnlek.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtnxnhemtw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtlroptulu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtjzymnqfa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzcmjuo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtufqdqoyn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gttzhevuik.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtfozysrzg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelkaxkti.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtjdwgnngr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtbfiyvtgw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtczxytkik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtbzwkzabu.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtxoeldxdq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtracwbdao.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtfpuvetwa.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngktppgs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtehbypuzo.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtwmenpokc.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtyujxvbwz.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtajbfwnpq.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtfbfmajdh.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtiacfbyqs.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtukccotlo.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtmsunflsz.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtfyllttyp.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtajawiyfj.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtngrsgyqh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtynxdzwhe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtlkvazwcw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtcqnuafwf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtizuavjwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtzqhtyyic.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtzkcbbmvx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtwbrdwpch.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtbpwyirvj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtwdobwuuf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtgthgcnhf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtfdxlbwxo.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtctuhymfz.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtuvkikpyx.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtlshnbvso.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtwkhcnebe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtgguitkyu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtturzamwo.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gteahtjegb.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtdldbmxrs.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtjhmoqwnp.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtduwubmmz.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtukbtetvn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtkkkcykwv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gtkbegcixv.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtvpsbjerr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtmzetwefn.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtixrpgbyf.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtbopzwyly.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtwukglqas.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtuhsfzxet.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtdtvuoxvj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzonxntq.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtyqdriarr.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtnsqkapkg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtqilklqqy.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtakkpmwts.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtxemxabgw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtzxqqnjkd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtuhvzenpb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtiphbfvbo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaqmilzb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtbtkjkydo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtgpxnocad.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjlpkbxqk.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzlbjlx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtjdpolmlr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gteaisorqs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtldmncypq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtuajddsbw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtpwyjqrhw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtjckfzjrp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtewfbscnd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtzpikigww.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjekziks.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtxigdjqos.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gteuoegqfg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtzrxbxref.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtwfaqlyqr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtianakqsh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtkttnmjjb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtcsrzaduh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtilmydilc.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtywpsomoz.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gtwukgpuib.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtkotbgsrw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtjpqhytiz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtdwuroxnm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtutkjqgrv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtpjoudlmq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtgtlqpkbg.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtkfrtnktn.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtwyrznzqr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtiemqugsn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgjbjlva.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtqeycqhtj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtuqjbnbih.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtvliitzrn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtqrpgauyv.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtzlcdytfn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyouxideu.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtsaimnyvx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsqaimgp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtzzyolppf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtrslomfoo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtcqmjnxsr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtgixwjlxa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtyalvlnyj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtvnptqnyi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtxfssygcv.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtkbykbjhi.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtkhjrkqab.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtykzrjdjw.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtlvaxlibx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpjupmmf.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtheooeqmr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtkmiabsxb.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtgducdska.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtpdsngmrl.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgqqsuun.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gtdtfbuyfr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtrsotbspa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbhobmwp.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtkfcuyncd.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtvnermcxi.html


<!-- 参考信息 -->