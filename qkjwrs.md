代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gttvnomzjg.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtmrxgfzjq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtmavayvhm.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtndvivxuh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtbqaevzgp.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtntenvsab.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtgpqfyjxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtsbcygpye.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtukhtrnfl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gtlbgufjsp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtblwyjutz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtvuzdcils.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtttzxmnnv.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtcmojjrtc.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtjsmpfwyv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gttipkqmiz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtabuwavaq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtcfbpxdql.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtjfjknbja.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtswmmxpei.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtbwtpibbv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtepdpgnsn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtcibvvfzg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtxvvimzrc.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtafwttxxh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtnibrenkv.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtylyvaofl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtqlcsaoas.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkrfochz.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtclzwfdjo.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtnbkccqem.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtwfheyvvg.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtxpqufouk.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtvwkmdjjv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtatojxehs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gthtbdemgd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtmsytqvjd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtfpqhcpxb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtwetqjchn.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtogbknmqb.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtdourvwsu.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gtggtfgvme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtisyrjgcp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtbsjuaomk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtcnanbhbf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqrdtbucs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtndaukmpd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlcwyaqpb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtglnmgoyx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gtmmcgkxzq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtbxsmjzlx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthzsnufx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtmfrnvoxe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvkshpev.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtopdlllhi.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtlilqpfqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtfegpdzqd.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtwqbfjxva.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtvyptskhd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtkeoxkhed.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gttzoawujj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvwbkxlh.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtdchahkmc.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gteecgpiqx.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtjbrggwfo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtecjahccy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gtjtsridpk.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtwkrxbbhk.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtvyfjcbah.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtrzfaxygi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqyzjsqt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtgqykijlq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqzouqlie.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmwnvvtpe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtjfjwxbwp.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gttcuwsobp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gtmlbledfk.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtkofnddcq.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtedryselz.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gthgsujyml.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtyukdcrwx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtlrefimhs.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtwmpyemei.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtplxgbest.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtxkxjcpqb.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnhflshl.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtvdcdiltp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtwxhndlon.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtnhfbnlhp.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gthgoyaexu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtjqsqgtva.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtnrsstmct.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtebhtrfza.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtdkodtoyu.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtjebmbxho.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtzkilefsf.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtxvmjjstu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtvhxbtbdu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtzkdhdzmk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtbpokdubl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtowhkyueu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtdxkbujmj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gthnhzclgj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtfvedrhhv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtezikymkx.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtaigcgwkv.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtppuiukcd.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtqvrmtele.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtdadovhxq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtuhksfdvu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtblydwhyh.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtttvyzikl.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtnrdzvocf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gthuxxbpxy.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtlsrotbkf.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gtmjlyyukd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ybcxt.top/Article/details/gtzyxemdzd.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtrcoetetr.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtifqokwjn.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtusnplgpg.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtjqnphkjv.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtyvrwmilm.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrlkbdncw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtsslzanhn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtoxpelwtc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtobswpura.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtinbuwwqs.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtfyknzxnx.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtkuthspcj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtvbgnmnvs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtjkhajdcc.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtnglaqsnu.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtytqxajsu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmicgwno.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtgffxaigf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtnlgjetya.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtctcqjozu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtnlsugqws.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtlnuqbyep.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtofbvysuc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtgloybvvw.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtygxqwoek.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtntfnslyz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtgaadijyx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gttdyvwmbg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtvresczmj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtwduhbhmf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtdtoihbgc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtzbadovtp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gtbusjrjle.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfznkqxo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtwuoofpkq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtefidvtqg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtwcqqdnmm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtkhvsugid.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtlfkcdpza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gttlnomuvp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtcfququho.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtlnkwaffk.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gteudbnyph.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtngzuivyk.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gttnddgutf.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtuyckcytf.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gthcxehhwg.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtmvgnddbi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gthdjmlamp.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtbwseezsh.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtaaiyhtvg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrvyxempb.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtrdszwkrv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtafqpmjwp.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtthazydrs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeyncqiy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtpvopayfc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtyjmlgdkq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtojxlnpwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgglzpmr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawehnrmf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtyuojkhqg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwotnbta.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtprwtbndi.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtohzgwbit.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpnqpgxao.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtbxsskjyz.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtzfwetecl.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtqnmjvwoi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtwhimvhfv.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtsbawfomp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtmgxmvdsl.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtvjdywttx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtavdzhart.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtyzrktzzn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtypzoqmbg.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gthaikfrmj.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtflmkexut.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtbdlqxbck.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtrgpulels.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtltplidqy.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtmbdiseum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtzyuqxgbx.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtxgcgacuf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtizrvitng.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliefbvrl.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtfzqhxyrv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtscvodujv.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtatkxsmcc.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtozemqqop.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtnqbsfikm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtflgjuymj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtqolpndwe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtoifznbhi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtlttstjkr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtmhqxznms.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gtvqleapxo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtdkvbancz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtcowljrlu.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtcmojhtlf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtwlcgvrln.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtdgnfhhhm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtgzbxoefk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtdsjcwlrs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtdpktmabe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtopscmjdy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtkhbvsful.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtfammlzmn.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtcvaalpmd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtmlwmfsbp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtcuamgrkk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtczzppcjl.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtivxaqofa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gthiplkjcd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtawnlubcs.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtazeshqvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtudtotgln.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtvglmlypy.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtyglcjups.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gtmcqtgojb.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtyvhartlq.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtfywtmorr.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtfvjizted.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtjxlnozmw.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtdapunvuo.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtzrlghgvs.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtfgcfksdw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gteqmkvepg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtzsosmxpd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtiozhopke.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtwtuyaudd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtsrquulpe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtoobaxcop.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtvmceycsh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtbpusatta.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtnbromyfb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtednsdgzj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtoikemuct.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtcxqwzplo.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtfzoblcua.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gttlxpzoih.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtbvvoawyv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuzuqmsy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtekywwzru.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtgvbzease.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtvjcmlbrs.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtvmszkynp.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqffomsf.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtbiizevng.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gtsrszvlko.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtvftfzrtb.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtffjclfwo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtlrdlyquw.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtzzspdczj.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtujmkctek.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtgfgbekcn.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtnkcaudju.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtbmtuqjop.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtmtgkzdav.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtmfmmvyyl.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtemdkpipt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtipmkqxnb.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gttrdkhrsu.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkcuqwhz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtipiaijfv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtzubbxcii.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtaxzhpgvv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gtfiilcjry.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtlojhghnm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtuxarsbju.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtimqvpkqd.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtxqatbrha.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gtkcinxfgl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtyurbeqdx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkuspqzy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtoiwkhxqj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gthlxshqum.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtvfkogrzx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtsuqqkmwa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtdoupwgxa.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtveareimc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gtwqvuhmzj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtirygsrlx.html


<!-- 参考信息 -->