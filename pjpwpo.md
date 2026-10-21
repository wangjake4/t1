代发 wailian999

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gtgfagwayk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpulsjuud.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtchpnwqbc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtpnslzlka.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtukdgztqb.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtvcwrwipb.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtgwamqbuv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtadeqtxif.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtzzhwndpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtqpjiajen.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtdctkegqu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtvxncvpcc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtfxwhqqot.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtnalocypm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtjhqjnbfu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtnasmjjew.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gtecjzeqda.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtrhlospuv.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gtdmrztile.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gthioysvei.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtjnlpxlqz.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtlhfdckzz.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtdnmfgalc.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaiwvajn.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtomkchiur.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtjbhcblmf.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtjjialakb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtiunemuer.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtvojmrfiq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttcoonulz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtklrxrhei.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gthcbqebek.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtpoozwhqo.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtztvemmvt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gtbmirhwhb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtvgroefpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtuedcfsha.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtezzjfows.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtcohxdpki.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtiafwumsp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtgbxhtrjm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gtxuffdtna.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtkojmtjvw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtgscdvmzc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtohhtxgwg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttcoudmvy.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtongfugnf.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gttkwjkmua.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtryoahhdo.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtzvhvpghc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtgfshqtmp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtjkaixcjm.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtovterapp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtlrpzzuju.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtgkpoekip.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtullyfsdi.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtglzhbwtu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtovmgpzrh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtwkrmqwot.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtebqbideu.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtxvjuqvpv.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtyypnmqas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtgzjvpipw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtjgdglfoy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtruswbbbo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtqesnckdl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gthiwsmpoy.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtkhcehbgs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtshboxcou.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtgahbklbp.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtigceipcb.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gthgqlbubm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gttwgshocv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gtotjyklrt.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gtxgiqznnh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtuhiyxydd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtnooreqwu.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtvzyoxlvb.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gticknhpyw.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gthxjsdjqb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ybcxt.top/Article/details/gtkabowfzg.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtowkmfsmt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtxdfuubqf.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtdtwbiuse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gthziyoxop.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtozucowhs.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtjuibdued.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkgufdlf.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtqbdxfzhx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtlfdytatl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtkugkvuug.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtnmenurhx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvenxxfx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtmzwrrpqq.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtxotlpxpg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtyajmzbmz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtucffbbvn.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotrswvpq.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfzshrkaa.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gtiprlqxwa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtfqxjfeht.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtueqspjdj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtlzsnugyi.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtzykvtbhe.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtirbbexnh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gtifkfvagd.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gthvhzbjfv.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtxvrdvfye.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtjssnsync.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtebmpzjoh.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtuosuhibv.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtluwqdpli.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtcazdaion.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwbujrxad.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtiqxwunsw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtjtvkquyv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtbyymospd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtcnhqkxaf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtdqzciqnf.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtecngyoaa.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtkshxsejp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtehkrcjcs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtcezrudba.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gttyewrdwa.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtckabjzii.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtsltwxuqg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtzrzqeneq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtlrlivlly.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtasawncxx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtztudjkvz.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtmrgwxdcs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtxwubglot.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsdnoykp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtsuygdshm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gthjiflhht.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtszprgqvt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtaamcyvzu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtcridjeud.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gtmqpvucqz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtmxkgrdow.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtbtrcvyhq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtvvbzyxdi.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtvfxtwzda.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtzxqypweu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtyzobsyzg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmoohufgg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhlcvtwk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtjmavjwzz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtxuzaxikr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtudfpvzbi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtntcyjwpr.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtzivoxrly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtsgdwjdfw.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtyuxeacgg.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtufevjgei.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtxbllmoas.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtnxffpcbc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gtjyevueyx.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtoffmgoon.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtmrejhddc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsleynsii.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtsmzqwynh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtukweviov.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtkwgaykhe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtcnkdxjpp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtctkmudwc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtpxswrxvq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtaxiiefyw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtvqqadmws.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtimuzewie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtzbcvwthb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gthefsdwfv.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtmjrtajdv.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtzymojgfa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtjyrekqby.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtpxqinhky.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtrxlhmnxv.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtumywklcr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjzahdqw.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtulqmkupi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtsfpkioar.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtgpcxvudo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gthomikbum.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtumjevwas.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtcbbklyxj.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtnpakhapp.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtvierytsq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtaqupxzej.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtatzhpkhq.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtaukqwrly.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtiowufamy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtaxugfrcl.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtqncmjfzl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtnyqknj.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtoyimkejg.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmkxnapm.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtobkvsxji.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtqcjunshj.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtmisskpyc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtnkwkcoaf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtvkaipvhv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtybheqihx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtkwldwlkx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtpaqoepwr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtiaxsefuq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtowjtomik.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtwednhswb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtjlirmjpr.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtyricefag.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gttzgntkct.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtimfthmmn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtolgblrps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtymogrdhy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtevrrgkjm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtbhijblvn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtrcizremj.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gtmvmpltbe.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gticxbujoy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gtkcycbazz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtnnjlrpnh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtznedhuij.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtxikevfth.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxehsxgne.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtkbgggkfd.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcebtynzu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gttaollqfn.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtgskuwlon.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtqgilazhb.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gtmbppxgln.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtrrpawobs.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtdwlkptok.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtvevuuvxg.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtqiugnzmu.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtxzfwqzgw.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtadebpitv.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtkkpxlbyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxrffbnt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtltvmwhue.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtjwnxbxta.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtfyvfwgek.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gthadupbym.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gteilwhmrn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gthuhzrsaq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gttklscbhk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtmviessfc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtowjbrimf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtzmwutonf.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtozcvsekw.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvolqfim.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtetsvtxsi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtheizqlmf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtpycrcbar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtnrgpeput.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtacsphxdy.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukuezxct.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtzatkxerx.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtaralteav.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gthptifvwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtappiekqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtpstulfsh.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtbravtunf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtxwyfzjkt.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gttiranzbg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtpmavctoh.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclbuesxs.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtybvqfyrg.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwiaykoo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtteqanmqo.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtcmdlsske.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtgvphhpje.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gteqxuvxrm.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtqvwkckha.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtnweyhppn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtwwsbinrn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtopkeddyu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtselrpfzs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtavflmjmz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtmcraugoe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtmjptglyd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttjobcpnt.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gtwhobqqok.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gthgfdonsf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmnqerrfc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtowlggqwk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxeavxpp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtbtiqgglb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtblnmlseo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gthoxvcurc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtlgmopvht.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gttrqldtiv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtxwbripez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtylnldnec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtloelqjwh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gticeckflz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtdfynyntl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzgshpyct.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpwovunlq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtytuggzlp.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gthuriobmv.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gteshxhiji.html


<!-- 参考信息 -->