代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gt2wvyoxuoo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlprzaqf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2rlgywpip.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gt2tvkmqdrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdguwgxb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqbtbrvp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rahosptt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gt2vdbgbfqj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gt2ocldcmrt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gt2kekcqiwb.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2orrqkhqr.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2rioyilfs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2bxegahel.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2xpjxljjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyhtygpm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2wxtzxvmx.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akswxkek.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2dzrlylkb.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gt2zjizkzeb.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2mmxpxisc.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2lxvplyzx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2entviwxz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2pbpuwcpe.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2mpmdfjkl.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2hgvtjnxd.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2vnkttlyg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2utkbnbre.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ymigsofv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2beqqfgok.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2djxlcrwg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2tptmvebs.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2dmujdokm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2hgwsltop.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jamkpfvk.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2ozfhwqsk.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gt2vdwtqkbp.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gt2qmowwokh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2njhtfyzs.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gt2uepegrno.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gt2wckirnuz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2wvewhlbb.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gt2qllqucvu.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gt2lffelmpu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyfrjbbw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2oiixcppl.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2vhvttbfq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gt2ihsummvf.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwtabmkd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2kultfbiq.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2nqbppiyh.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gt2eiquviaj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtvkvehq.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggaytrsy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2ycelbwyc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gt2ttigbpkg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2bqvrmxrz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2zghhfpua.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gt2oylqhfpn.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gt2uryhgahw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giyzjtln.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gt2enrovjsc.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gt2fdrwdzvt.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hthzbijg.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sinzdxqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2rucfkzvc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2dmwnbegj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2dhiqtnbp.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2pkyqxoko.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gt2mxzzeooh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oebeduex.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfpkxkwx.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqrtvpwc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2nggmjrqh.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygqhqugw.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2vyegckgr.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2funznlrz.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2wxmytsre.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2aytfmdqb.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plxihcwh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2gzvxswmr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2wkeceqxp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2gsreyeln.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2qqzxpzyq.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gt2zpazdgzk.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2smzwiynm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utgqsfjr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2cexogjra.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2rqmxamyr.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2aqdqetpx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gt2eyakjjwi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2whhvlwtf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjxcukix.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2cekzkpya.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dquwfnmn.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2pfsmexam.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2rwygocsm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2edrqpxon.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gt2xczyleyb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmnnqukk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2tsrlamxt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymbmeafu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2zebfebfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2zpyfbsib.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2suubufoz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bufthgub.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xodojsjo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gt2aiszzzbv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbitsoeo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gt2ijdhsngx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vopvunzw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gt2oqbnlsgp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmzyumok.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2rujgsyso.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2maxpcclq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2ijyyrnga.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2xpcfmgrl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2omazbwni.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2qpbetkxd.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2obktullk.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2hdbknari.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2eumyouuh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2vlrqiedw.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikaotaiu.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2uzlgwpgk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2iljamsna.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2gtsjuadm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2tindlvta.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2illolelt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gt2dzijucjs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2hsecngte.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2yzyulemu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2amrcvhro.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gt2fkntoowa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvkgjddp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2zlbvoprz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2fxftuwtl.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2drdadlcq.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gt2fiyxvaev.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gt2spqoykqr.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2qmouxtps.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2mxvwvqlb.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2jsakcvsm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gt2knbhkbhb.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2tdpkteqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxbgwzse.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2fbjcpuea.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gt2dsdbbgnr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sewthchs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2pivibkqo.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2oauygkzb.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2hxirwdmp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2bpeimieu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2ogxilelg.html

C#:   s.Substring(1, 3)
来源：http://dali.mhx1999.top/Article/details/gt2itjrofzo.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2ahotujol.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2nwnzovqh.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gt2kunmddbl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2qttiwont.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2xvwqepte.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwcvemxw.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2bwiggwpr.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2zizqawfd.html

C#:   s.IndexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecfsfmtu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmdaiqhc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2snadcijo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2guzkusug.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbuxwths.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2kqhogtzz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2oczsalpz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaxibiwd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2misrfymi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2tbgqoieb.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gt2pvcugwso.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2jnpwtutm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2hkiqjxla.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2gdqzgmqz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvmkmxm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2itouqgol.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2mcdmouom.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2aoxgfcyr.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2xrrggccf.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnljvmmw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2rsclcioc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2tvtwiauo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gt2dypinmtm.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gt2werioczz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2eobueahw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqxvljt.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2yrlzmueb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2ikirxblo.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gt2ghuaxweq.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2zijfjniv.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezcdgjvd.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2qgzcdrfp.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2xrnczrle.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2kbujhjzb.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gt2kabxdebt.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2qssntqco.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2nlhbsakc.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gt2nppzfhks.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2rydxmttk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gt2rbxhpoak.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gt2msxjxntj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2njlfiwol.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyafnelq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2icehbqel.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gt2zbgdzyuv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjujxapk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2akigdftn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amhizbyw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2aoizdunm.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2orehucog.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2rgbedhkx.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2oxzaelna.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2ficprppx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2sipvjggf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gt2jpchhzmd.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2cfstptlq.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2ueqldzqm.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2eaqvdaia.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2stbozayt.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2iyvplhzp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2mmbcactr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2lfbvlxyi.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2fqvezlxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2ptfelumh.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2mubdjkct.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obtufsqh.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gt2lnkjlxyd.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2dpfloohk.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2galqdmeg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gt2goyhcmyc.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2okqqggcv.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuobztc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2lfbzxqfd.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2zhwfadtu.html

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gt2pfdcvies.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gt2ugkjzxme.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2imhpedfs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2jphkvyqc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2wlqodahy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2bktppteu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2pmhtjlsk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2dkddvnwk.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2vbuicpnu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2mtissfwi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gt2lzotabkh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gt2tbiolhrn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gt2byjvnkxp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2ihhtbzyv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2fhugqmcl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2oggfjwxf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjmtnfdx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhezhjn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2enkbsxgu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2jyzjtavw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gniadvyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2utxfglpe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2ujoadkuw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gt2ownspjdr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmxslqnb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2bqvtarva.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqmxtxz.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2vvgkxint.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gt2alsgjidq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2slbezcuq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2svgbtero.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2xzijjbea.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vibjtsii.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gt2ohtjpygb.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gt2vopqrcpj.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2zqgtlkfr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gt2vkeitvtx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2rkctobkz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2xjrjgjuh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmeziigy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gt2lkwztiri.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2hilokrkq.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2dotmnpvx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2sqghkiyr.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gt2kwllxjxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2uncsrcod.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gt2opigqpqs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2qcpaxwzy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqrpzbav.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhcjsehr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2argseqnm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2zodxczqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2euryoqps.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2twmnfmwu.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gt2klavhmbm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2gihmpokt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2amtwbjbm.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2vncoqxac.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2cpfbbare.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ukdxnxvn.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gt2rnkxaxou.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2vdcsqhlz.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2rsmtodyx.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2bnvlkjlz.html


<!-- 参考信息 -->