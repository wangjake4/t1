代发 wailian999

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gt2iafpgvwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gt2vmdnepdu.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ajxsnfdy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2dnzgicin.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azsomvzn.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2nnnsfxhx.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ztrrzxeb.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2leyuvexx.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gt2avokudjc.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2mogyvklq.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2uihwiyty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gt2clnnincm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2spypdzza.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2upqdmdke.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gt2dthieioi.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2hpnqfkkt.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gt2vthltrit.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2srutomfs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmiqrudm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gt2khjsqboc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2nhacguun.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2twhwxraa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2zfuwcsly.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2pzbnmmqe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gt2bvfmuowm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2vlbcgbli.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2quzxullu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2wmpidakp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2zcoktsuu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2bdkaewov.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2xulrxxyp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2gcxsluin.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2oyiloxqh.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2otjsavjh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2zyqdvshr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooiczwrs.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2eyhrlonc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2ailjbxlc.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2qgewpheg.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwqctowo.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itouogss.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gt2lwuzdmsy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gt2ikzzavlq.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2oewmuypo.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2wpfppwxb.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gt2wqgrhsjl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2mrsgqasp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2diuefjhx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2sjllhxgr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2rphmzrxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2ggtueffh.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gt2cqkonctw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gt2kkbywfkt.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2fjmiunmz.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2sgcllodd.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2psbhbnoc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gt2lvsajvlz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gt2typlndjp.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpvbkkkr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2nuapcihu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2aupzrclm.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gt2hauunwiw.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2fwaalthd.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gt2yypwhlbg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gt2kyxbfomx.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2esdlpttm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyucxtdk.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gt2unlzaddr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2twhqsrcx.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufjiutao.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2qvnfwtts.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2vdpgzvnw.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gt2xawhkmer.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2mgmggkck.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2bkdhtuiq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2shudgiad.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2kugzifqg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gt2oycmfxhc.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2goddgxjr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2wjlwjtak.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gt2nvbmzxxv.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2gkbfmimi.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2qvotfrxj.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2nmuciiqr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2stdfgtzn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2nndpxvce.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2nblbejzd.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2hewqcses.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2gvpwreqf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gt2mmolmqfo.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2nxjxmapz.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2evuprfhf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2gnccwjmp.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2ptqbutpv.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2bvodbcjl.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2mumjyauu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2dznhdotz.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2rueabxco.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2dickvvex.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gt2zxucyeua.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyfoxzly.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2sliktkes.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2fprqaehd.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gt2qnxqvzyb.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gt2npbjyoaj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2qkdezhis.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gt2cajfhtja.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2cucwmuhx.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gt2xmvquvca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2klpqvonv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2hbbjmbhr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2rcektpmt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttnjiida.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2bvluezkl.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2pcjndtjv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2yyffasyk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gt2gphgomsd.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gt2tsxkkvdt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gt2jqnnldos.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2xwmrsxlb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2aiyegmly.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2osquliyi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gt2uikglodm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2yscbcvue.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nitsftgo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2ypgaibke.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2xqcjwjnp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gt2gzlxhxct.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gt2smlwyrng.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gt2qwrrandc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gt2sottbxad.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2szlhqmjm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gt2uxutjdwh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2ebqtpgwk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2efslvzqu.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2bkyyjfkg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2jpephonz.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2pjwppbyy.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2hgtlzukg.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxzihrur.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2zcxgeksm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2jctpoarg.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlzgytbd.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2munqputb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2soqossue.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2ztpmotxc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pnzdnozc.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2oqoexnwy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gt2mmjqxoby.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gt2owibvzkw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2skdhgkvo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2shdjmfgk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2ewnlqhwf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtvdsgpv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2ycxxdiry.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vszjxbnd.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gt2upffspdj.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2sbvjmafx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gt2qdwjspfd.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qggpqqlx.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2amfvnxes.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2xzpjnidd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2kndfzcqd.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2zhunhmlj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2vngluhxa.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2jczyocdk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gt2jtxniilh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2xwhhfyga.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2ezglpdfc.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2bruviiys.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvrfjbxo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbkodjqw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gt2pzjniizz.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gt2nbulxvga.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2raabaxxm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2cdwjxmms.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gt2ovmyhaqj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwzfdjk.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2xqflvltb.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2pykfmqwb.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gt2gwkiyhzz.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2pxjuwzkq.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2zuhhatgf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2dltirfji.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2mdumvjlz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gt2afipzafv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2vohwgyni.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffrxrhwp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2ycfqxxrh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gt2ihazcsgg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2iweqbojj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2owgqyeit.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2raocxyjl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjfmbhgv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2tqnpwpry.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjhdfncn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vomgwucy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2skycgzth.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2agcawuyy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2olkmxycm.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2muujgsoq.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2xqxpvhob.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2vkmvuphp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2ykojwbcs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtwzweni.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gt2crkcetht.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gt2uqdoaupk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2nxtxzfeo.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gt2fygqgckz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gt2zgwlaptf.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gt2evkokmuq.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2rfadyvlc.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gt2ixguozjx.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2gfykiita.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2zvffpprw.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2sgomdjwy.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2rtwtyhxt.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojvaqdwf.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2zifmvrgu.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gt2aybpytra.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gt2rsxbwilu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gt2cxdupxlq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2iqltfjsd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2iwvonwfp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2vkqrxkwx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gt2fndzkbtw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gt2kenardas.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2ozjabumf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gt2bzrmpada.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2ytqwgodq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gt2njmlsksv.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2hxlmclpe.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2ivtxuzgh.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2ltiddwdv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2okryhibo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdttpkmy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gt2tdoagvof.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmyqkfie.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2bygxwzxa.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2hpdmlsll.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2nxlvsxib.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2xwmvpywy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnudhbkb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gt2bolgycin.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2tzsipqhp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2idsvivut.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2ceujnnms.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gt2sactazfi.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2ffswgzji.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2rruoaetv.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2hhkacryv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2kecjcicp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqjymnzh.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2ovuaaqnj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gt2adqkvqtw.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2evymvkjh.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gt2zxjhduwa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gt2gwokbrje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2triyrtep.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iecxreud.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gt2qlrbciae.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2ppkpoivg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2muzohhte.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2zwvlghyk.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2xfsviusx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2vwjvuazp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2tbfsfaht.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2dmhdtjsq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2igqagipr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2mcalgwdd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gt2uuexmccm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gt2ljcaaezv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2wqwmpcss.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2vdwmwieg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pemsvdfp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2yhogqsjw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gt2jqtzzuff.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gt2iqjkwvxb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gt2soxexqts.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2omkjdsje.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2vsxwdett.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2bbsjopoo.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2hycgznov.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gt2fwqvbywx.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2yajgzhin.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klcouyok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugngxxvg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2zsrhbxmk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gt2ikmxccuo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gt2qxwqxmcj.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gt2aftblbzp.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2ehnmflhx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gt2afxxrbtm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gt2rjdmxrkh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2azaazpwj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2riiruvgs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gt2anwrowqq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2qkzbusqf.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2fqcplsbt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2obdllgdj.html


<!-- 参考信息 -->