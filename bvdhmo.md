代发 wailian999

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2goviohfv.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gt2rfbggafg.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2mdheunfz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2exmjhlac.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2nhismkvp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2hfyvxqth.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gt2gojnqyoy.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqhvkenw.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gt2otkcbfdb.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gt2ppgowosj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gt2ppencqjm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gt2togxvrib.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2pdvtsqnm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aollsokp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2fextznyn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gt2hnjsnigm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2oxvdcidg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubjeowxn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gt2guywhoeu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcahddch.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2pdtcsnkp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gt2lshwkyds.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2rdphxkmc.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2txnwuqlk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gt2pjutyztn.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2dnkvlhvn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2spljadkj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2xblohktb.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqlpjscj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2zbozvocq.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gemmjgza.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2afhlyici.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2apjkqlqz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gt2ezumazkv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gt2tclkdaxt.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gt2sudjnkjs.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2dnihdutf.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2sighqqek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2mhbruter.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apqtmcuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2dglbappp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2tjkxcydp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2nigrwkga.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2aztxaimc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2pxompcxw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2hiupuuoq.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gt2badsonyp.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2anijqvjo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2zuafqsdw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gt2dudjghbk.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gt2jsqpcvoi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkxlazms.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2gzifbuzs.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gt2schkzjyj.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2lvqhbhbq.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gt2gdslchhm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2nqqusqiy.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2bhqodiei.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmqposez.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2jgfzatnq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gt2eipkxygb.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2bztxhzcr.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2wlhkwixd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2pykeisjt.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gt2qdvxhuwf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2mgecdqps.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2oixzktgx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gt2nfyryiqi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2gxxxjepo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2wznaqwfm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2etdfywuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gt2zeueumfs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqmkeyxs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myuzsxxi.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2roukecgg.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjwwbzmg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2hzfzrwrh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2ivyssjcv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2hrqgvjyf.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2icwbaauo.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2aplymfvv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlnbwosq.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2jaqcptlk.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2lrnatrnt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjjcrfwy.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2jdutpryv.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2uavwatpw.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2pxfbhsfe.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2nachdrqw.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2dqegbcxj.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2llfzbdhv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gt2dferqzro.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2tstygsiv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2ozcjctly.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gt2hbvbowme.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwnigjnu.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxpgsjjc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gt2rkxjuhaf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2vcaajntx.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gt2padveucg.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gt2ovhocfat.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcfkvrai.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2llefwlhq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2mehvemei.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzdjsclg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gt2xthpwaub.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2ypdgeslg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gt2cocfwscg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2rjimgbkd.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gt2xkxipwfm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2pubpjzjh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gt2jtjtmzgt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sweek.top/Article/details/gt2gyyxeymb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2endifhis.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2rtbmtthc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2yldyihlf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gt2mbsazuuv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlprpeoo.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2upekdckz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gt2jwgmotqc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2eviwcndd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gt2pxwnksez.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2iconfsgs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2dhygeukr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2hdmhitps.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gt2sdrxiomd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrfyaksc.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2erbmrutd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2hgvhsalo.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2pjyujyqo.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2amngqfjf.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2muruukjn.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2suapksss.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gt2nbmytrlg.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2kdclppxx.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2gyotasio.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cykauwqf.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2hehkfylg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mmdsofux.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2awptgkub.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gt2nnhyiqdp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2fizkzkfx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2rawrczjw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwazicdo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gt2lxunbtjr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2zpybksyu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2ojzyhpgd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2vcszuqbl.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdmnelwj.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2uxnhecyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2cgfurbsx.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2flolfaej.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2botdsybg.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2thldufvl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2hwnlfoyy.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2ycdxpavq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbzvrmkc.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2rbfaxlbq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gt2yqpgxlfs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2blrdkkav.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2emjewbdv.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2hnfbzsqk.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2fxufrzbj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvtqfufo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2zbnnjshv.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2tamdtzen.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsnujuxf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2jgchpmto.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gt2lwmgiaqv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gt2auhlzbkc.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2eshxkeok.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2qqswiqkb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2xpuugtuq.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2degrpvje.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2rokhvkkm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2fmwddhmm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2vlmbbvxs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gt2ycddesyo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2dqinpbsd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2apvtsptc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2qqdoupdy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2ekyigzpa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2rfxfehww.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2iwappahc.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2nsxnjntl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2ypzknigg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2kqfnrfxj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2oppjepuh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2jqfrycee.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2fqwozovn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crrbaczd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2ahnhlxaq.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2wnyvcaww.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2xorhzsez.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2zjlmsjqn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2lyttxipv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gt2lrashvfy.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2neuhvpla.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2dfgsxnxi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2vckuaylg.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gt2xzsyymqt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdhwctug.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxpgybzg.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcqcczxc.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqvtipms.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2drtgtjbp.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kinrpiwn.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2ijxnaimq.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gt2xlklrpwj.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2xhmelnjo.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2pyyryhbi.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gt2qsaeghed.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2pflhuboa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2kaljognp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2vxvwvlal.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2pcfhzkjl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eickfoih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gt2dahjtjxp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2qnlbozqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2qkqqxowp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gt2uqvsytdb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2xkbmrxia.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gt2pnayphza.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2yfmastum.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2dcaxczon.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2urnekjil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2fldgdrmd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxzbubkz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gt2udilnwyi.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2yzzbrnhv.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdlagykw.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2pkrvunbt.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgwjlmfo.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebnqhamo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2bexoptgb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2vtfmchmu.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2xvcluwhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2vwnxqtug.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxnrtjym.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2iobxuest.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2wfponlhy.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2koutilqg.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2dqzktrbg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clvlnzyg.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sniikxoj.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2zmqacjhg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gt2tvyghwdn.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2vvrkxynp.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2apuxxgqv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2ijaieoan.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2xqmaqvxf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bldegxrx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2lvrddtyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2ywjereqq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiltahns.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2izseenlr.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gt2genmabcy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gt2esfufejp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2icglqefe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gt2mfnkctkg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcdvvusc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2ppweghwv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gt2tsarubly.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzgbsbzo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2naqsfkni.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuodpluk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2kcefojpb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2mmgplbac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2ymoopllm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gt2hdpkxunj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2cmsoulmg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2erqpepwl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gt2pcjmssmw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fawpmccm.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptuyjdqs.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2umnceicm.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gt2gepydkvj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2ggkjeqhz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2siepqsnx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2enrclpfn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2dnbiiuti.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2yopdbfcm.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2xotjcwye.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2bftyvwkt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2cujamjzw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2ignxbkcr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ihhdqyjt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlfzclfg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2rxjftmvz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gt2aqzgtzbv.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2idzbssuu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egtidtre.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gt2qquiwsum.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2vlvwgqlh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gt2utuufrky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2kknbbxlx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2ecsucbed.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2qjmtkumz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2eioqrkrx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gt2eehqcfoy.html


<!-- 参考信息 -->