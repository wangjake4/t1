代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpsvlmcdb.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtkmwwltol.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtxwhualdh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtpifkgwzk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtrjiinjsc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtnoiiqjsh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtpdlmxruv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoduguibb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtmdjzyvbq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmbzdvce.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtbaliwznd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtgugnrgxq.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gttejhokjm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtvdfnmcrk.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtdylwmvnv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtndwffexf.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtvidpysyx.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtewtgivfe.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtjobugizc.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtmffhwhcc.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtlcgwmsma.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gteuuczrpg.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtrkcttoan.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtouscgflt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtqyjvkwqw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtwykpjugc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtmlvfmskb.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtogkesojp.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiemfmnra.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtojusucon.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtufginldd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtycpccsnm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtbawgtqpw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtrdjuliwv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtichkevng.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtkdqflx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtkkywfqhi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtrsawivuw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtqzvetfkj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtkiyknlvg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtfagxpbsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtvjhrqxru.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjadjacuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtvstnkerv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtvyclvfpu.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtznodincv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gteunknlwi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtmvhnsjta.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtczfxsflu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtkrqgvkcz.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtjjdrrzeo.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtskcidzmf.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtiywrnwsp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtyhwqsjnt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtczfdcvzf.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtzkojwxni.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtsjarnvxa.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtunldzlzy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtfmkupwxb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtrvnglkoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtclpuzvrc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtzdwfxfjo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtaqfdjppe.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtukzypngl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtoahlbmzy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtqibtuamy.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gtehwwlmke.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwixkfoxo.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtumkbuaeo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnumgvwiz.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtoqkazetp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtuiozverw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnpqvrgur.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtyzucqtfb.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtygijpths.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gtwulsefty.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtnvrdoxsb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtsdjhnpab.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gteboasmqf.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtfqvhzksg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtqegxgfrl.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtpuigxzuf.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtkujvzyzb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtuyuhtock.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtzybeiion.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtxxbmmucu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtkglhytvc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gtfbnvbysi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtipgsscki.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtjbbynkrc.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtvolboxmk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gttlxgghld.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtfqbovpqf.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtbkswvsey.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfxxwhtj.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtcbmtzvhm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtlgrttywv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtkounwuoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtqdgqetdl.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtvroaxbhz.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgcmkfol.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtrcgbrgpb.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtrrlbcaiu.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtjftyulho.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtszgbzzoo.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtzlkcsrzi.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtbniaavgn.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtbkkrhwgj.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtbwcprtrh.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtoljeistk.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkkodmdg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gthbkuzzhw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gtaikdjavy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gttxzvyumr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzocrpvnn.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtmdextcng.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtzprpwedg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtwwioktwm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtdtdfjyfu.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtgcrnerrv.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtgoaxriyy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gthydxfbve.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtewqbucqr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnagaxfbq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtexyhwugq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyibzvxo.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtjsjhpwcl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtrdnqzoim.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtpsoxkpvc.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtamfbfila.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtmqhvfiuv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtabnwigzb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtmjzqugfh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtofjkgjlt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtqbhbleek.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtwtzgmfnt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtxviensuo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtiilzcwdb.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gtoiecetva.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gtyzyljlfb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtkuaqfoms.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtavryyuiq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtarcfebjy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtalbpxhix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtrhuwghbs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtkgopequd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtjhwsgeuj.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtdztytodu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtvhdmorbt.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtkccsitrn.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtporvthjv.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtkuqbfyig.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtovdsrfhc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtecywyycq.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtdewxaxmi.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtezagqgme.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtczcmumcu.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtsujqxace.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuetgsadi.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtszaxruwi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtvvzxcbow.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtsdffleke.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtvivnfzgy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtpkguvsez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtqrrtggmb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gttkcxvcmv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtlrwqhold.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtoichyavu.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtpcefdndn.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtuatilhbb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtllghubgm.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtiermuxop.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtvrvcrcpw.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtrblkayzm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhjeiczt.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtkuzempub.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtoebgdydj.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheqwzypc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtupategux.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtxkplyqbi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtzwcccoca.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtgmngttyc.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtmfsvooga.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gtzfrkcioh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtcmspisen.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gthwzkutnj.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gtxafoicyv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtnvumqael.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtyefinlug.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtpfadikzn.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtuofcsquk.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtpyzthcie.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtzqcpifxn.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztkwqpup.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtjwgbrsak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtwpplgfdj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtgmzjazcb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtaqfeihsz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqvzzwdx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmodjpof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtxrltqdov.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtxgshpxaz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtixwbsyra.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtclrjtsxz.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtwmufrlrs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtuhhrgkfl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtczjamjdj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtcxzaxpqx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtzfqkefrc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtebaarjbd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtupiysgsb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtxthtpmdm.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtxonveoph.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtwarefofz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtendmonxy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeqjrxdn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtfsaojxrf.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtdxhbxjxv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtcvgnrpnr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtvlqdnxlv.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtbimysytg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gticizdxju.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtlobqlgfa.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtmxjpphjc.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtvtyomdnx.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtjtwtdwcn.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtargfxhpr.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtquaqutef.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtniaazobv.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtpjwurzex.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gttxkcnqsk.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqzehpab.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtokzryvgy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgmbvnrla.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtyzbdavpa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtldowjfcq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtiikquvmf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtcmdqbtdt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gtozossktl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtgmglbprc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtzsghgbzc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtonraprjn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gthokpqccg.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtcnllgtxu.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkltxmvz.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtcbuxlfkf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtnqwhgfao.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtmsscwrmj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtakrhtuzv.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtceiguwjl.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtwipvedsw.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtguvbrzkq.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtitnnkluy.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gttwgqqqcm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavqihxie.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtbdityseg.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtmdgdavsk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtjctwadjb.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gttfznbnae.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtktxgydkr.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtkkmpirao.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtdvmgtlqw.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxctghiz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtyudpntqc.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtilbcghmk.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtnjsvogws.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtiigwfrkh.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtahruyioy.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtkrykyakl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtkfmikfwn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlxrihtho.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzoqtysr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtybhuasiu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtytlbtamz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtrcmwjrin.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtasrolgoi.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtoehcxlsj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtlittsyhu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtlszlhmhu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtgjmtblht.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtwoijsgku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtrzvrycrf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtfnyzebzz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtlbzrgdlu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtwupbolxq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtugdnfcsl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtqlxefchz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtbbpwhrnc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtlilxjiay.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gthmnmdoix.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtdydbitbo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtstjanatt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuhrtdzqg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtiaitrlzg.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtfxoalpus.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtplemnjrp.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtohlqezju.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtroggikrf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtfacofyhz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtazejlsey.html


<!-- 参考信息 -->