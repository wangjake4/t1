代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtiltjkcik.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gttlkcwhch.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtswapebmw.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtqviyorcj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtolnvfkqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtsiyiwyro.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtdbbeolil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtoeumzmgy.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtgmprozhc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gtmawpmimu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtkgizixxa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtzmqpizfw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtvvilbcma.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtdbxzsrne.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtnqedkjvb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtuocmwxtn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtybkmviit.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtmurgpuue.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtmhrqopfb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtpbkkknpp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtdahzkfnn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfufdebbn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtitqowckj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gteycymsjx.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gttqxapybl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gthcbrgsqu.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtspugpxar.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngcdklpb.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtkczhqgeu.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtmgtjaphx.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtotuxwicf.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtvdbwocze.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtgwztfdqn.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gteizaatwo.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtqqxzjbyo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtogtnkeuo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtopenakyb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtygpiqawk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxshswzd.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtebpzwost.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtkqohlsdk.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtrrfnqxua.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtlodhqmpf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gthteunesi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtsyhzfmiy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtfmcpwovb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gthskrndmm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtwptccmfz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtzzwppdwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtxgwbyutt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtdhrbyxrc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtkkzhssrr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtuqjmjhmg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gttrvkjroo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtzwtachpf.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtckxzphma.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtsbqlpaqw.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gtrjofcgru.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsttmxnlk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtotszkpke.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtsgtcezkw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtjlqbxqgv.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtrghwkphg.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtzorrppob.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtwxtuwrbl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtnxwnswvc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtlgzxntdq.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtzijwvrks.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtjzqydlub.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtxwcuydzr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gthgmqeprm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gthxdymgdy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtxdpqdpxn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtoernwqyk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtrnscspse.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtmfttbugv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtwsnslgsf.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtdjsvypok.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtbpbmioqh.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzvnaxzuz.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtaniwqyih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtsfrivpnz.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtogvbbcvg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtvhxykixv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtykqbildj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gthwdkipzc.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtnjzowucw.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtdlpiuhfp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtujfqsanx.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtalsctmsx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtukkpadxj.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtzwejojak.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtdwqyixqh.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtucpwcqvx.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtizsgsejw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtkjiaiizg.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gteqshdwzo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvkyhrgdf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtilnlwcuy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtbidarwkb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtbqqyhqyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtincloxzs.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtjcdcmkvr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtpcnjahzm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtlmwetfot.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtnfzcrenz.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrnqgpnub.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtwrguptum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtbccitcgu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtuefnolbp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gthopcafwt.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtwsazewmy.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtrkjkpcbb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtplmizhpz.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtaeulcqwm.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtsfkosefn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtncczwfhq.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtwzjguddy.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtwaeatlee.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtxemlnpgq.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtpnprnizr.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtluzenfhb.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtatxjmpby.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gttmxyzebu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtiotvryge.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtjfscoryf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtjdlammig.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtlchkgrdw.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtndundlfq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfufroij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtcgrajmuq.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtpypprbwj.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtfzgzcyvw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gtkzpqhlix.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtoyaejpfw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtkybbyzlo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtngrmucup.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccrarwgr.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtutzvijek.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gtpcjbffot.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtzuqejsif.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtsnyfbbkw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtbedhcjib.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtmwvusfjf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtweqttulg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gturdtxdjb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtvapqgnig.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtvbrukejg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gttedpmcjl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtwpwledhm.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtukktyfbe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtxzwztqak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtvrjvdfwt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtmyriqdoh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtyqmfpcog.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtaahvrysn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtacmpjkln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtmsccffhl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtybubcvtr.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtxqhpsuxa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbmkrcvu.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtzgorievt.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtirduvucc.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtjnimkoop.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gttlgmtzho.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtiroxgaap.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtqfengnat.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtmmnxexhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthyixpytw.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtlrazxvec.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxihnhfpu.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtoeqpbvnp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtgqvnqdym.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtzmxzmnvj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtmcuopwkm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgohvicvw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtzvgrscly.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtbhnvclfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtduicsqqg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtofukijzn.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtsejiccdy.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtneddibij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtcsernksw.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtrayrpkyj.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtgueccwik.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtbqkdxfqm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggviiynj.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnzbwjyv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtxwjymdqp.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtnbzsrwxn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtvvooewfs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtotnyqprx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtofpmkbii.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtaxmkwrvd.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtrbsvdzlb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtlmctbiab.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtggbcrtvq.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtgntezxfp.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtgdvgwrwh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtfdnpojqg.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtqjyfacbb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtzhtcrzqy.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtntcqdoqb.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtrtgpbnuu.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtoxwwzhty.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtlnrvigen.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtjdkxjwni.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtquohvnvr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtdmodaibl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtwyujxrkg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gttrmtigeo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtzcmpampt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtjbfvoqee.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtfgfqikwc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtqdbrxupz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtxqzqglzm.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtxzcakltw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtsvivblny.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gtauoyjvuw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtppdamcve.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthxhgmacc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtteespoig.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtcaxuzsbr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtwgnaluoe.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtywkyfxwo.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gtwokalzdr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtgdismybg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gteqvqdisg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtgbjzrxtp.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtlvqnwcuv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtavxwykuk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtonrieqnz.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtokbiwrqq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtdywzoejl.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtyfqpsxei.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtgzzimist.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtzrerdanv.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtcciajbfy.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtsskqzzut.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtcfivvhrm.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtksqrupku.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtqxvjnkcq.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtuvqebwie.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtueotpwut.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gtrrfwdljk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtbrnefjnh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtfpfzxpes.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtwozvxnzp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtuqdcenep.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtapzpcrro.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtdaaqcrfg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbianloq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gtpmyfwilc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiejyvlbv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtspujfhjt.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfhufmxs.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtzssvfrjh.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtsoujqjcz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtmiieycyo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtunfxoqtw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtnactaufr.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtqnqrmcqh.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gthxchqmja.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gthnzvdsvg.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtygarknah.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtasjrmpyx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtzwbxqxwd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gtkqkseucj.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtbfatndsm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtetvaskwo.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtjncjdiqe.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtphygkroy.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gttxjkcioi.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtzwyjyeuz.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtodspkbls.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtruivdukm.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtehdhzqol.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtjkpfxtuj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyeiipyj.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtuoykyuvb.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtihyrzuth.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gttjpwskmr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnxqpucl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtuokckvmv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtxlcymwej.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtkhgvujtt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtymczfgby.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtoubazejj.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtolkknejm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtocjqcrhs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtkjptkxcq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.iojbl.cn/Article/details/gtplzvhpnv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gtoqghyxas.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtbekjefkb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpoyphdf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtjfhwyyca.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtwpnmjspz.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtgncmtgdf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxszndcr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gtytvykugd.html


<!-- 参考信息 -->