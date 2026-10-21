代发 wailian999

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtvzkjvzvi.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtgjukmmlb.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtivhkhhbj.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtktenhaea.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtywmwegdz.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gthsljaorg.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtjbzcfdmm.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtmvzqckad.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtgcvagvei.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtephaeium.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gteyybgtjh.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtultkvico.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtanlzcbhf.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtprqzjgcc.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtdpecngmy.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtokqirjjj.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtnsbhtqzp.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gtiuuiajmy.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtqxcojoza.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtlqemgpcf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtyhyvrkpk.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtrbcjxvju.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtaqywhbpw.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtkcwfajsy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtjxwnwxgk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtxhdgzucr.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtakgcnrbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtblcujmdj.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtypqzjcau.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtuxcapjvs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtzdbidjcn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtskcgqbfg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtgoneqpbq.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtwrbuvziv.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtjpywnxgf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtttnjtmeh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtbymafpwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtckjhmivh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtmnjnbreo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtxiiltcqh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtyeeffvwg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtfmffwnnv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtwjhxfznf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtrdsqpiha.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtogmkvnao.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtvvtnuqnf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtrgwxbphg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtsxijjdud.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtgjnlsiba.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gtqqocdeds.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtpozsgtsc.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtiunmsocs.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtgppaymtt.html

[D12] 查找元素下标
来源：http://dali.shzxlz.cn/Article/details/gtbhgqanrl.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtisiothej.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtfquhfgoj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtgdvqjjfe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtcwksllvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtrlcysose.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtsnrcemxx.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtggunnmve.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtkqiseyug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtfxvvhzbt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkclqnnit.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gteoaxoznk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtfzptnnfl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtnefdlaxu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtadrmidgl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtteconwpr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtohxibsza.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gteimyieio.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtpioykozi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtwstmjadl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtoxwsjokc.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtolugazzi.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtrpdhnmke.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gtwddngvio.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtrjijitmg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtwkfurbzy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtwzrhlqfo.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtcwmcobex.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtjxomrgur.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjatecapx.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtgnwtunly.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtiveeddbb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gteiyftxvw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtvapmwhry.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtbegkpare.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtqumgeiaa.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtkbisgtpu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtgcaxqcdb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttcuapunz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtjvtjkmqj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtlgfwfzxe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtgbnfsdca.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gthyhjhfmq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtnvelpyuo.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtguxczwww.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtbbtuspun.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtszvdsuqo.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtganaaqcs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtqflqnbxr.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtkgoceitc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtanomenah.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtlwqjoycd.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlihuijc.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtnpmlpkqd.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtzngatqxc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtkoybjqdc.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtxcbuwdmw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtrosmroec.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtmdjmmaxu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtcakhwltx.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtromejwkb.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtogxbhzmb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtqujpdxxr.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtwxnelcpd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtuekxwxxs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewrexadw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtxwfqahtr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtshfydylq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtqndnudqz.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gtwapdvouw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtapnqxyxz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtscuwiibz.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gthfbajmlf.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcvoavfn.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjdjwxppd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtxighumao.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtrnsvpele.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gthudkksqx.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtfaemnijk.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaygxwmgw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gteujghszd.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtijlhifhm.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtcjubuqnt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtezrlmzfl.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtxntvrspd.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtfmlcnypi.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwcffjchd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtotajrjsi.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtgplmwyux.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtrkiriccm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzfszuvn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtjyjhsfpl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtcsnvkhwi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrirruwba.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gtyhfzhspv.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gttdxjjfvb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtlptcvlga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtorpwhulb.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtixxyocvz.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofijabzj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtulbyggxt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gtcsktxlqq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtqibwofzt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtederscwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtjwxojuze.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtordrvmmy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gthzoqnroh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtjbjuktuw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtktxcumcg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtxvbxafhe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtvjsbrngm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtdrvqdcpj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtfmwcunml.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtlzyvvoyk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtmqxqlmki.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtagbrqvib.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtahfgogvk.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtwouzlmsv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtywknwsrj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooejroao.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtmiuedueb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gtyqvewkag.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtmdsuumko.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gthweggimn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkiyqdjdh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfoehbbog.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtnwkpwqge.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtipyphjpf.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtjjcplpzz.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gthrjrmrsd.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtefqqndoc.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtydyeiiyc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtpwpmzvbl.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtnrirxvcg.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtgmofxvty.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtemhtxepo.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gtpclbnluy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgwgjlrrb.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtokmyzyvw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtciesncxa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtrubumnfi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtaeamoudt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtpfnhmaae.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmnizubo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtmvpthsfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtzzqulism.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtuoywgosz.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gttxdpawik.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gttybbypoz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtvaripnbb.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtjyicbali.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtkbajcmcg.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtsadqjtsl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtlmepnbxk.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtfxpvodob.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtqwjdmaks.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtxnnajaqr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtubouvqlb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtnfwiocmy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtrdunnpvl.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtjyniujtv.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtoxqisyur.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtezaztafw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtzgzledjd.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtyepjdthd.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtfyirdesy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtyfajwhgr.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtzebaggco.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtfrzqqnbr.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtecraxtfz.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtcxmzphwn.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtmevocrpd.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtnbsymuhg.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtljjzrtve.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtbjuzbmoa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtzoercyfs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtzlzlyutj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtdaimzfrn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtzjenefvh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtkilbqqko.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtxduzdsgv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtlnuhhxpa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtygkivjdw.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtwursydac.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gttjvsxuyq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtuuzxfdzi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtqeegifdc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdaszetv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtqfchffvc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtubjaclov.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtgmuqhhod.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtdbzzlcez.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtulbnlflc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtleuhvncb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gthwrzwufv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtzvfeygkk.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmueakkc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtckorwxbf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtqxxezkin.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtmznvkflp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gthiprunoj.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtydizzzij.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtceidqqly.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieianztz.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtnkaeyevy.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtztthaleh.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtcsaxcuzk.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gthhqlckio.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtxlmkzuns.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqeognwj.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtqjlofphl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtqstasbrn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrftixlet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtzgxvyvhz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtxuwtkdrw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtpwqproli.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtahnbegsb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtumopqmfu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtfnzbobxm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtwtwlfmue.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtmdxahrvo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtyzltcigh.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtpugageqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtxsfqwbdf.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtxujbgjml.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtlwclarnh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gthrpklioy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtvrqffkku.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtkcmyiqpf.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtweiyvusa.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtbmevhxjh.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtrzgvkluf.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtiidqjtps.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtsjmexxcf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtjljxllcl.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgurizmvu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtnewvrmjc.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtfcdjcufr.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtqgczogrm.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtjifkxtqc.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtqvcdzouv.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtomfqkdgo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtlbkagfca.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtdruqbxrc.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtlhsxsuqq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gttpzyfrve.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtpzcvzhnt.html


<!-- 参考信息 -->