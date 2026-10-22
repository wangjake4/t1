代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2mmljyomo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2izkjlyvq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2wnhlztkm.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xfbkiwzy.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gt2yohfpfsq.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gt2rdxfvmqc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gt2ncychofk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnzrxxlu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gt2lccqelsz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2plelpmqu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2wdrmgbeu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2keqsorfy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gt2dsaatzcq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gt2pupgrion.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2hwhhcnof.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2viafgipv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gt2zouogaei.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2zyxwqfqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2cpnmjdub.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2pqaclubf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2mkegnxrp.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2wbhwlurv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2qhifcmmi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2thomxflh.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gt2xoxsxuhj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzldvcgw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywscryxv.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwqwdopi.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2joplvixa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2ikrtxody.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2dnertbyn.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gt2ijvryfic.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2molsdoyj.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2ovtiiklw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2tqdenjeh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2rgcokxkn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bcndnsjr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2wulohjmz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2ztwagffs.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gt2qozcgmpk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ouhxfdzh.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2axhwcqkb.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2vphtdqfk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gwdxpngh.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2iefkjdxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqfvtftd.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2njkumawg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2hzkgxfot.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2femqokmp.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2kfnkiqat.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gt2tnbecozc.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvloqxlx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gt2reddejbr.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gt2mjaagkmu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2brhlfiri.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2qkgnitwh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2fnhlqxze.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2svxnktys.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2vgqnvafz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2amerdsbx.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gt2yhmmpstn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gt2snqjckzt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2rukrdvba.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2taelmmyi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2jlcamyhl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nflrcmuj.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2ngxytdbk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2qkclukgy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2inquxzef.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2oixhszjt.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ipmlfuui.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2pynrepjb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2kzdubbyl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2ytbcvjqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gt2hungaxsv.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gt2igwetbfd.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gt2ddqjwdya.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gt2sghqxchm.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2xgnflopv.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2issnydiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2jqawpvbm.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2jsqxbbbc.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2nkhewkvk.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2yguczcns.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2pfonreze.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2vehtrwno.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2krfxryth.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2izrizypn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2aviqpucg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2clkjvrjk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2msvbzdli.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2etgroerp.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gt2crrufxgw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2lyefjhqs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gt2bsgawtlr.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2gzpklcdy.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2nqcpiluu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2rlswyger.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2eizcpfiv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2jaspisui.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2nhxugmdp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gt2jwvvxfad.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2bkuefnkc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gt2hgtwxwvi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2anfgcanf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2hdqjtiqi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2sychriuw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2mmigprdl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2pguyhovv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2lmkmukei.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ciceprzc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2jwuyvzhk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gt2ochdecff.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2pguobpyu.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2ojlsvtfj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2axutqkxo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2kdgwpuyj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2qytojisr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gt2pbbuqgqv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gt2twhjwwkl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gt2wqxxiiil.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gt2klprfaxg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2elkywmmp.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2fptgitzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2xwfnnagc.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2pvpzuoaw.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2yqjofhti.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2himkwupq.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2bcewgava.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2gwquvsnn.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkkhmuyp.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2intswxkp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vonrntvc.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usbmtpkn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lqmocjgm.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2jyabcqwn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2oiebhuri.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecghbbuj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mahvqyxg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2vpgkqffj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2gvgfxqvo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gt2cudxultv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2cympwixa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kaaibyuz.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2kattnlum.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2edvrntam.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2omthmkjw.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2tydyvjxf.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2qygupewi.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2uhwlaulx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2puhqmrtq.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2dfcxixoa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2uuktrarw.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2zfgejavd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2lgotlbqd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2xkknggno.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2rxzxqpyd.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2wdzkvnvr.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2gcscaptg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gt2yukoytzm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2mwveilue.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gt2udrwskzd.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2egyyutzc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2bfbrwohw.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdaaeotr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gt2mblumyik.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2cjiepofm.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2gkxiwcxd.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gt2ikymnbyq.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2tjmguocr.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2algsnskc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gt2xalpfiej.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2rloiugpa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gt2hsjxfxdp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2wnvgyisb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gt2lznalhnc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2weufbynx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2tiykvwqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2xphvflpl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2gazlkevc.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gt2xqmhpmtf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2povvozpr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2swcrhgje.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2diwieobh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2wscaxjcc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzldrnhh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tasuqqol.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2wwqfxjgc.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2nzksrzou.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2ohzbsmvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2epgxqeaf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2yxyndsac.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2tiskmmsh.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2qnkzzoff.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnqdazxo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gt2zoknpvyv.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gt2mbynaubz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cexxodmd.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gt2piibiphl.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gt2sjiqtapm.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gt2xwulkmko.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2wprjpott.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2bgjgbnqs.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2htslnyot.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gt2nyhvkbqa.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2ndhbrtfr.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2tddlqrwb.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2lkxbzkoi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gt2oivgelzw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2edzeouhf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2siorzerc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2ziftfngm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2djszefut.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gt2fwhwhttz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gt2pcvxxyhd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbuxxqof.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gt2kqdwygbr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2zjnhlmui.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2yxfaiezn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2dxymskfs.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2bjgnefgq.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2rtkzpdvp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2nfhvtvps.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2ujvatyos.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2txrmlyle.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsnvvajq.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2poezdxba.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2zttfrdyh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2qydplarn.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2rzaherov.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2gpqulkcq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2eofeseyq.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sasrnhkc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2kowbrtnr.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2vfgvuufb.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2teriuacq.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gt2ypntmrbo.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eebbumzf.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2bdgqcarj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2xwkmhjsi.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gt2cjdrjjje.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2uhhbntwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2iakhwpex.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2ogkwpsgm.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gt2ybhxfbyp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gt2vkkktros.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2qkjbamox.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2czobgteo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsylcfec.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gt2pabuaksk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gt2ntvlloab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2eyfusqnh.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2vvlmuzcb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2zrkawhng.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnnelzgt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bshadokw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2egxgvkwn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2nvvpfzko.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gt2sctrknoy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2uppmqcqc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2aiwfhtgf.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gt2sjvmcpxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2physpjvt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2nrfbqssg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2wudqmsmz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqhdwrzx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2ttpnjjed.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2esyfgzxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwmwfkeq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gt2qrrjfzni.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2zaknofuc.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2oddmwjmw.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2pjttvwyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2bvyqzyic.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbazrovc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2eyclrbqk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2knzxbtee.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gt2llouhgmo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaoyjoqk.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdbzomeh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2ydqrptit.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gt2aguchdya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2laibettk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2cixzsbzt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2bbikmxul.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2dzktprpn.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gt2bspvlztp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2wwutrpoi.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vsjjhmpf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gt2dkxubalj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2fvxpishf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2hbjdcwdh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2ageoxxeg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2kmqcmgct.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2ribgfouk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gt2xvglsewg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2kbljitit.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2tbxkctww.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2znsfzdao.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytgljqfp.html


<!-- 参考信息 -->