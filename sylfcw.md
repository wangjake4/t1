代发 wailian999

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtyjnocquo.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtpcqqtccw.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtzlikrwub.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtzfhctvvf.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtwgvhaxeu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwryvin.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtjasyprgx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavujiaei.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtjoukpzer.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtymbbmiuk.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtocsajrro.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gthczlhxey.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtjqcrxpjz.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gtqvahwspp.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtoyfyljck.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtrjbuzoon.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtcidjwsxq.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gttfjrjtlw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtzztnldlg.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gthpisdovw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gttddslzsm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpuhtfwa.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtseudauvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpfgyvur.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtcdisbasv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtdqmcpsgh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtefntierb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtijfdwmrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtrblndeoy.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtlzmrznka.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtjbcthmun.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gttyqaaxng.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtxocppbfx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtjnzxnsqt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtjthxiibt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtcmuyvsci.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtsgzvrrqa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtncwqtvsd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtjmbqyatm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtxhkcelkb.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtbbuxofqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gthyfeyphd.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtagydurpe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtqjaggqye.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtzgxnpfsv.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmksjeudr.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtymoioeeo.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtsyenjerp.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtggkmpixo.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtaflzpdxn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtqqrkliyk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbqtgbgtw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtfhlabbfp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtmolytmxe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gtdtyuyknc.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtsedusbvk.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyqvpdev.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtbzofvrey.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gtamvmxfjs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtiwfbbhqy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtedepjjfw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtvfqegjef.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtcpcnpnhq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtutmibsnu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtplvtqgzn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtepmkessw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtskqlwfho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gttbngxaqa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtolpjcgei.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfwrqmtt.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtrbzzeyyu.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtapxsuwko.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtgihbmbyb.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtjywimkvz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtuyjayoqz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtnffruemu.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtesubekax.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtylhrcvkd.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtcrkrrihx.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxwvfyri.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtyokqlknf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtlxeqyfec.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtpwkbgcxu.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtrnjugxkq.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtkcpjjeaj.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtnhjtnyuo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtxexegvde.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtjoqilcft.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtpgnbnyjw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqoovsll.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtutyrcfex.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtdrkyjgyn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gteggnppfu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtejkjbzkz.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnbyzihs.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtneikrmvx.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtymfhwzrp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtstkreffg.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtmwxiaawf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtegogwctl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtywpdhiux.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtsnndvggh.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtrpfaemml.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtrgofkvre.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtpczayyao.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtdnewygll.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtqmvrekek.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtxmqkljap.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtkcepfmjn.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtutbephfj.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtqayzapfa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtkhpvtptv.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtmuekdxpb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtnxoptqpk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtdesmsbmj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gtyckujfts.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtjigaqmev.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtvafqnray.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxavzfcbb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtkvyezylv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtiyknfrvn.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtrgbnkqiq.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtrayziupd.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrgbrhhmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtqxhkaudb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtantovswx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtmdfdulhq.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtdbiegfzq.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtuxvhfeua.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gterdphlwg.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtnodzetfz.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtegfrkugs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtqpbaxhzd.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtxtxbojri.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gttefguugr.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtzozpkosc.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtfhwarpas.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtekllkmne.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqlyhweg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtexvljkab.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gtkutfvpfv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtxwssynwi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtakiivfhi.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtqmomsnki.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtxatckndl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtodhlgmvy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gtrnmadfoz.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtiqhojuac.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtpxnziamz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtmjokmwgg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtysrxhupi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtecwhfbpa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtkbylvose.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtjnlyyyti.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtkmfinchl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtofoncdin.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtrwibdtjh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtmqtblrcn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtzbckebkw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtcidtloph.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gttphyanvc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gttjregkqj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtuvgkujck.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtbhkfwggb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtpdbqtqga.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtivrmqwlz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtpluylzjo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtdqfgabzg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtnsrzmnej.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gthhunkqke.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtsbwhpeov.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtnxtdyzzj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtaiiuoedy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtcalwoetj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtofrndcgq.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqvblmfa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzjrmmmt.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtiuygtgwo.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtlqyzangd.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtfuzmbthw.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtcvuklshe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtehglxaog.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtghajljcj.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtuwbcojao.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzcefrdpn.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtidxefktw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstuzdxnj.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtftdazdut.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxmkuozj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtbporkzim.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtidjucjzh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gthdshvefn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtwuzarrsp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gttxkdhuex.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtjizkzvjd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtwfvvdgqu.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtznhhlksm.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtawsenest.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtbydgmdgr.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtudsdvsoi.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gttahzrlkz.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtgfiqjdqi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtddmfbiil.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtybcxqxpi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtelrbsktc.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtyihqulzm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtqitbmdmm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtxkbtesbe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtgcdzkdrr.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtlfbkcbyg.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtmimokkue.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtrhdwupei.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtlcaekvng.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtriphfvtf.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnazzvqi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtzglhbtjw.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtbuknojke.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gtvcbqltze.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtbvcvaqiv.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtuqfbotuu.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtljbiwayg.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtonavftev.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gthjurcjmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtxrxpcwlk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtqvioctch.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gttpmgasla.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtkccrvvls.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtaytctyec.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtichxrfmy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyybfkaus.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gtuodtdckb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtbjocptwg.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtqvgnbynv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtplxmpodg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtxxdpcnlq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtejgjsldf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtyhbmsism.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtutlyljps.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtmnrcqalv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtphxrbfzd.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtpyhiwdae.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtebpikszt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbwqkxxa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvfphrgxz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtqsdootns.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gttmfvucya.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtjusdmcmg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwzztokg.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtwmzrssfi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtfgpbkmmz.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtaqvdabcb.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtnqmnobpu.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtnrmfjlzf.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtifnwyuww.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtxcalovor.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtfdijkkpt.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtsidskmyp.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtwkpsgrdt.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtlhouctkv.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtoivccdfm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gtmjlxktqy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtcukrrrtl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gthhhmzfle.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtvqikzqwc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtloirytfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtuelficbg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtfkzqvdzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthawpcowa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtdvhkmkzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtqzmaowsa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gtotguqakg.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtakbyxidp.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtpqelfpdr.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtujvlhbbe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtwguowuuo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtykkehayu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtvwaugvzy.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtxytlcvcp.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtwqjohzgh.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtevkabbjz.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtgpgzbebg.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtccjrhmca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtiutlryzs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtwvrpyoow.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtyltaeekx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtwplthfjf.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuesfshzc.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtoigwokct.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtyvkspokz.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtxiwhawhb.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtdrnzatet.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtjcqephpw.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gthwatufvf.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtoosxdzht.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtnafnlqan.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtecwozvmo.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtqrajqdwi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijanmmbx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtnrgmqkvl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtrnbqryak.html


<!-- 参考信息 -->