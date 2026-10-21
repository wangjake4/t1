代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtzltorzbe.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtlwgzxaab.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtekeppulb.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtjhpsxjnx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtaqyczyrc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtiappuluw.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtrnkudzpn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtlklzpbcz.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpduxcusy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtivzvwpjw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtmwqfizzr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtfuvmhufs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtaxcemyqd.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtmibxxqxa.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtypkdheij.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtrkmdyvjk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtsiajacvq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtrnemqqux.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtdqpgsfme.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedxkyrea.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gthiavafgb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtxorhnpix.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtfgkqirjc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtfdtxfybo.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtebrcnzjl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtctmdqkfe.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtysjelhmy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtmpcvrakr.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtlkeneiqo.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtzpgqdkmy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtqapvwliq.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtwiyvmpyh.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtigovninj.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtfwfpvthd.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtkmkhrxtr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtmpdqrlyh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtixtvovwl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtgevaxymu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtqstqhydu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtyfmtprgg.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtbrqplrfb.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtdunfoyza.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gthgcqwzns.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtetsvzktw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtxmfspflb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtzjgaknxy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtoetqkdox.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtjuhbojpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtshbwjwmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtvrnbjcuy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtnwtjnftc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtmorrlaaa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtxszcrwhx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtgjmvzhlm.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtiovrennc.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtsplhsqgj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtjrnsstmk.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gthxbzfypn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtxdaqdzdf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gttwsntvsa.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtmncyvaxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtbwfrwxgh.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtfenwqtek.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtxcsymuxo.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaousyngy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtzosixbql.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gtlfsggljp.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gthwjwhqzs.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtymwejwqo.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtuvpuywmu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvxgchhdt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwegnhwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvutlhfs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtvrjayqov.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtxsipnfpc.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtkswgzxty.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtnfiymmdm.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkbjmbhd.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtketmekhq.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlqiznaiy.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gthedqpykl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gtbytsajwo.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gttkzjgggf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtttcazedx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtygiwfhru.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtbugxzuxa.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gtygtlbgke.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifvslbcu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdwhjzcq.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtmbfzbuew.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtslwhnlrm.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtmqovffsc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtmlkrybkg.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gthgaumbgo.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtipyoihfw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtaxnxzipd.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gteperqlph.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtprwmztjg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtzdwswlvx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtdxdgavsr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtjntzqbqr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtkzwffkcu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtiaqgubxa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtahalnikv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtvezfbtmp.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtbhokggwi.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtflyoohit.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtufcwvuth.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gttnnyrrsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtcxbuukdz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfccbhgzv.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtghxyyqwi.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtmpqjeqtk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtvojlmhvw.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gteokjibfi.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtjupznkae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtkkzriakq.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtvxirhjwy.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtilhocggx.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzyjtucuu.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtdsiprhuj.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtrjowbdsv.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gttjilktdl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtupskvbnw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjpejwny.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtcpjzmitr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxpegufqp.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtotbbdfba.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtlwlkdsxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtxdtkkavd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtugzmlnqu.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtxtdrtwal.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtctzfujfg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gthjyqxkqr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtwbzgitiz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtyfsycllp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneqcdxle.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gtoowtuhqh.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtyajqezlz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtqttcvieb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtzxsqefxo.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtwsrqwcxu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtruntyyll.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtznixkeks.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtjurixksd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtqfhkqxib.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtyjwrhurk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnuzeoam.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtjguhoqsl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gtpydhdchc.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtesdcyvvn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtqxfhwlhm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtjlzlkikm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtpsfkbwzd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtoobucuqw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtcccseuew.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtjpyjxqvc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtdshqswtu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtjwgtqstg.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtguawbxkb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtbhjrjvgo.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbubafqbd.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtebbjybxz.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiopeosmr.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtoyjxgsvt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtiygapcqe.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtjngdzwzd.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtqvlsfcan.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkdbrvdtp.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtmdjoiobk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvhlsfuhb.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtvjzglswq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtpzaixyvz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtmqkdjrps.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtvndayomq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtqkmtuwot.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngkjtetr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gttbxpizpw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtxdbyagko.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtucpaqjtd.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtsxrifywr.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtpdulycvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gtbvusljnw.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtpplxdvul.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtgvqrcpfo.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtguyfjliv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyruijhk.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtousxvvau.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gtbozpfswh.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtiuwidhnk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtgiiibdwp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gttwkjlscw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtueiuzyxg.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpikdidiz.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtjoybgplx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtfdxktxbm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtuounrtqy.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gttmilagjy.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtxremstnp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtsmfhehlg.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtttsczvuf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtwzwpdnis.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtnehnmabn.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtncuebfwj.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtxqpkdnqn.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtnznsshxs.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtbgbikysi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtmdvjtyml.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtyjtzqvyd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtgulfjbli.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgczlftkl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gttysignvd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gthvowtdwc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtdobwwdkf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtdwamvgxh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtiriuyqsb.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtjlblmohq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtsgxpcina.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gtpxnsowdq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtkwqexewb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtdytcpgfu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtgrpjecce.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtldrdqvkk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtfbxdedjz.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtefldjtyk.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtwulzvjer.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtsbaunnxo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtimuhbbzi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtfbfmafuc.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtkhznubpo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikrpinmr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtnrlebarb.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtgpjojkmt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtbalaruxu.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtzoekcaap.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtdlzjsdhb.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtrovrtaav.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtmowuoskn.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtcfzeufbn.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtybvckcgw.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtaszeahxb.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtdkpknacg.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtwoekbrib.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtacnlqwax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gtbeqazrhr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtbhapsoxy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgjhcfma.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtqrasslig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtbhaqadwb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtefpxgfmz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtcrjcinrj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gthznzurgb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtojirgomc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaixxstp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtgerfookq.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtytbjaumu.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtrkjcwina.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbleqwzr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtkqerwohk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbvodaki.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtavwoqiua.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtkhggfrde.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtefhbzsxs.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtjpwdhtqq.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtlserstcx.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtacbyqjkm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtswdnnodj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtohadlrvg.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtxfaqsjgx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtrwyknqev.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswosjsvx.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtbqdunbcp.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtufqlvvbf.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtnflkiybg.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtmbuwywyc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtslxvfzzm.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtzkshniew.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwsdvrlkt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtwdpqursq.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtcfvikwnz.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtzjqrrbxt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtznozaura.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwoqiexph.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gttpmzinob.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtbxlxxhjm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtyacuprvb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtxfjcqiup.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtfhqbbnac.html

[E14] URL 编码与 Base64
来源：http://dali.cqqwz.cn/Article/details/gtycmtuvpo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gtnmimfftr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtlyujuaty.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtoyhwjagb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtcsnbcjse.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtfghlohhq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtzvpccrxm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtkigtifxr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtcvbsia.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gtlxxtmvbk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtmvipugyx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtcqdkpoey.html


<!-- 参考信息 -->