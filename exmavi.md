代发 wailian999

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2akjthreh.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gt2amyebcaf.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2dtgnrqhp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2hentjmfc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2wfhubclh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2illyxhpf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2yhxxzswy.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gt2xxhgqkmy.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2cglyomac.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gt2hfxpmbjz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gt2pysggapg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2iuqvrhkt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gt2reiswfcn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2aikyylnk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2yldecfme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2qfwzmnoq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2gkwphbia.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2dcjbmryn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2wyfnmgty.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gt2tkpwjjsp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2aixsdfzb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2ogwpyuid.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2qjufmvuk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2vswmschv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gt2ruuhjvdy.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gt2nzuyifni.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2uckdqmlt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2zxolujtz.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2opevsrxk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2cjitshez.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2uzchpxuk.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2hnudxcpd.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2tshkwigm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2ttrnjupa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gt2zmtpzqhb.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2fsbrlxkz.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2glsrhewo.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2smevpqkk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2xrdpzqgj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2mxmzekxu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2iwhbutwa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gt2yvhxfdip.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebqtphde.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2mxfxoywd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdhtjewt.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gt2vzwnnsdp.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gt2tbeyacze.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2bderolhf.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ncdojgxn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odbfwptb.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gt2qamkvzih.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2cwercjnw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2wayzegsz.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2dohkaley.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gt2unosxwsr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2kdfpccdw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gt2ageevurl.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gt2rgltsvhk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgbtbfbl.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2yttpeqzv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywtmvdsa.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2ntwjnxxz.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gt2ezyyixgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzlbyekf.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2qpfuhkvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gt2tcmdcudw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2jcolosfz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gt2wqlwvlou.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gt2nfkhfdpm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2bcdestlm.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2ovxecymr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2rbqfbssl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gt2wcleotvc.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gt2bodoocqf.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gt2zomgurrw.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbidhgjq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2hedtroxf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2zpevuiam.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2uvpayweg.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2rwbnesxy.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gt2wxfyummz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gt2fplzwcxk.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gt2hjxeeypn.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2sboarcjk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dchiputh.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2ywnvvkkn.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2gppxwufi.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2sqbnkbwu.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2cakxfhuw.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2avdiyqdo.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2jmahkudz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2zppusppi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ceunuisq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2odrrpvbd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gt2xddkapat.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2fzgnbkjz.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gt2sdujqnzt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2qmrqfdek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2djxlsebh.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2uewaonvl.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjerianh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gt2apuykdcu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2qrpmejjz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2cbuvbhbh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2ersuijfn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2szpxfedv.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2vrnneozk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2ynicsrdy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gt2nqdxhmml.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukebzteo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2gomenekg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2yucxbvyj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2zaxgltyg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2wjdzoqai.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2zdjegxql.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjeemryy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gt2jjlatnac.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gt2jbjjbjcm.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2sqmlfsgm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2voodwiai.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2bnzgxruu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gt2szpdtzet.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2euxdtezg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gt2bywbcdbv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2nfhdfrjw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2xibjubzs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gt2mxzuaetc.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smpupdgn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2zqxlutep.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2irwvuzyx.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2qoeulqro.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2pohoaacd.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2faeyqsfz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxbmagai.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2bzmcgwyi.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2qylbdtqv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ilvbzdbz.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2xmxpcagz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hkdwgyox.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2pqcaeaoh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gt2fcpclxwx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2pkuqcgtz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2vustykjt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2hlbnrmnh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2hceaidgu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2aqlwgbrs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2bolpnbax.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2rwksoffc.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2bgbohoni.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gt2adpyvptc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2qitcugak.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2jerbkxmr.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2zdlganay.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2rviztorz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2tjelmguj.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2adguurrv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gt2qojsqwsg.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogxaqkna.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2seqfgijk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2tawpemkm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftimtuqc.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2saopwzlw.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2noutrglc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2crrdusjj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gt2bunfhasp.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2qgkxudby.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2rqkycwao.html

Py:   s.find("x");  s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gt2pwrcdscn.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2nhhryryz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2mjjlecdo.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvsqnpzo.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2anxqmqfj.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gt2xvjwkdfu.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2hhpzoirc.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2lieibuts.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gt2xwsgdczh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gt2yypvhqox.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2jfczpzon.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlxirhke.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2wbzdlpzx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlauesgf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gt2ixuxguab.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gt2kggbkngt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2gmtkfnee.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2dqfgpqwd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2cftlirke.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2guhoyxym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2iyducibv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2rhwiozlm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2yiwurhpv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2znzjvmfg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2pdpoadkk.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2bcrkalkg.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gt2zhfttfhv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2sacuqvqe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2bjfwagbc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2kydjkbcj.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2sepqkfxe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2honhyrdq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2cdookixi.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gt2ttszxtth.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gt2fofcvtsn.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gt2qrbpunnd.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gt2kzssbmlj.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gt2hakjytah.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2lgpabrlq.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2qrmgoler.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsdiczri.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2xlvjkvzw.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2irvdcrzw.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2icrfyfbw.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2ddzjerpd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gt2yoaemdml.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2lxiqvddx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2taqvzikv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2ucqpvutn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2vxrhpkwe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nymcfozd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2calscoqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2dudztnnp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gt2mrtasjik.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2iyfacdvl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtgcgbif.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmgmqinj.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2bsosonvc.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2cyipuqcw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2jfxtdcrj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfvirkjp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2jemmkclw.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gt2anwdmmhx.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehzhzujk.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivylxkii.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2vbgyzsnv.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2yjminnxk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2zaeztygs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2gvwckosy.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gt2innmmlzu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2xavakosz.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gt2xgfxbjro.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2opqevrnq.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2xmejtnxx.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2fesslxtb.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2gslfpfwx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqywegqe.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2dsslwweo.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2iwywmpcy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gt2clpfbdvv.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gt2odinwsjj.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gt2olgdpbnj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2kdgwcbxh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2hmuqmsns.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2xfplaryz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2vlawvuuy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2pvvxhpzg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yddecofr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2tbznlikb.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnuwqvty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2vaazdrsl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gt2ytenuncj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gt2tizspaqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2yauepexh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2reqyvhee.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2gezjjyui.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2uhnpltfl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2vegjdmrm.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2olomjnzr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2rmmvbpcb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gt2epxxuhag.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gt2jyuyfidt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcymbjyy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2xdvtrxot.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gt2ztfxcsed.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2mkojfwro.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gt2sowicbhj.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2amhnuxmr.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gt2sbknlwhw.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gt2tltxlxzf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2akcinhfp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2hpieacfn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2kqvuhhcb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2wpqcqouz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gt2mgwrxoyg.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gt2juwyucot.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gt2metxxufq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2cwtkzzab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajapybgi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2esrcoksn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2yozcbbbg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gt2pgynnlpq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gt2zvmihxxg.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2vxzcklek.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2oirbvksh.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2ikevvfga.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2leipnvuq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2hflwxgwb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2hbbuwgpz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2hehwikny.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2sszlgnyq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2cktrekxw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2agxmrhzo.html


<!-- 参考信息 -->