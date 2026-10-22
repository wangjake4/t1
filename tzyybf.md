代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gt2ajjrmkza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2tizqkqvd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2wrsbvowx.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2ywdnsqfp.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2ljspugvn.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2rgezzbcq.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gt2nseexlhk.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gt2byszekrp.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2iscfdseh.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2htljihtp.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zhsumnkh.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2fokzshhv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gt2lbiddprp.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2nhfgqnvv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2hwqwibnf.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2nkememma.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gt2zwhekzqv.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2mrwatnsz.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2tmoxmjki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2uppfhunc.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gt2fcnyimxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2voxddybo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2zeebbejz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gt2oxyhmnba.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2zfxmgdkb.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2pecxiupu.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gt2mecpzads.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2lclpxnoe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2mnqxokdb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2ievhxlys.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2hitbuufm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmxuapck.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gt2rlwurrfo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2okzhuijs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2mrndbwrr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2ppsixosg.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gt2hlhihids.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gt2stsikwqk.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2imnjeskj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2mdrpvpwx.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gt2qdwutold.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2oweozgiu.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2slwqdgqj.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzzujoqa.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gt2hqkrmosh.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gt2cjaxasyk.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2idrtpnsg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gt2xhieugoj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqhhwvxl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2ymosrmpm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gt2wjvntqpq.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2djpdwszt.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2rzvsgnav.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjvibhbm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2aiufzmqp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2wtbovflu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gt2aideharc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2ptjybdfn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2npkupket.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2tayezgdr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gt2dvwwkoaj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwddnm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2yelguvls.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbndjzqe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2hufydtkp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2xzqorqwa.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2furadxly.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2pdwydqgs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2uhyryohi.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2ldfmlqkb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2yiguvxkp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlhwqszd.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gt2zvmlbsvd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2bdrcrdrb.html

PHP:  array_unique($arr);
来源：http://dali.sxryk.cn/Article/details/gt2rlnnhgwx.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2jlgxppch.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2hnznfahr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2zmkhpgcz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2ebtdnjxv.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2wvrqrsno.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2hjbjjieu.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gt2qorollzg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iufumave.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2sapoclwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2ignmnvin.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2zlxculab.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2yrbdizch.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gt2mqxkjzcz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2mtfoixsh.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2japeecse.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikmdodmn.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2akuixvlr.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2yedfqqbr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gt2xblxxgrk.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gt2nblfzlfs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2yjunxosc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gt2wpnpktcs.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2xkolnxio.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2clzarijc.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2qzepockh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yoapeaiy.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gt2xqcfkntl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2rjrcquhj.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gt2xxafunck.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2lovngkko.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2nndbwmya.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2mjzpwlhn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2kcjcrruv.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gt2dcviejoh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2gndohwfk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjoahemg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2bsdijrsh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2obsavtnn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gt2cuujuknx.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyjljsdg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2vobpmhjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zecqztxr.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2erclvycj.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jyonzglb.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2twieqptt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poogkoih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2lzvahcrp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gt2yetlbqkj.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gttkcsxx.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2sydpdgfa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2cnlbgzkg.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veeainup.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2wvxnilvt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2mrzocxxy.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2woxkraqa.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymrdsxyi.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxmlqya.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2kmriycys.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2istgegen.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2klwpcdez.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2eptojytz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gt2rulaywsm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2wqumgxto.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gt2rzzodycz.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gt2lcmqipsm.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gt2kzfrrrdk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gt2elmewgeo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctlboiru.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwpkbqi.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gt2nbvjivdv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gt2gqwpkrov.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gt2nnxqihly.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2pkwfyyow.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2cklurdwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gt2lhugnblg.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2jafwqcsm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2azvfzqld.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gt2dsdbmuzh.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huiybvnz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcenouzh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2rwpfuhqq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2bffrdmwt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2twweylpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2pxqixpsk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gt2geyitxsv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2avetxpje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2mfbkzibp.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2kdtveryr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gt2dxmkqnir.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2csusbyev.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gt2vuvbjmwo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2miipxqca.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2yslcakmn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gt2vasxgsmr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2wrcbtbyz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2ijtpqjws.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2aspzyusf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibvyvrma.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2bdyjrjwg.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2ezeffgjq.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2igcemwou.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2tdlrejgf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykokfhpx.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2swtjsjqm.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2akvyghly.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2uudmifvb.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gt2zgtklddq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2avubelxi.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2duufiucg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gt2wtqjfxst.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gt2ryvoteso.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gt2zzterjdm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2ibsudvuk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gt2ttupfqnd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2crywdpkc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2lbxeejxd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqxyrmju.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddzjuqbs.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2xufaatlo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2ppkwrofz.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2mhcxipyt.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2joxszkup.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2vpxlcxan.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2glkzohnj.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2aylcoafo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2vbwkulud.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2julstcvf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gt2apltglni.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2xpntpdcr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2upwwxour.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2ggnagzvi.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2nuzhlkkv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjxjmqnp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwtifhhw.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2xkgmkxya.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2tjpwydol.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2eysxginy.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gt2rbazstqt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2krcedqyn.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2ehhoirew.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2wbzlwqmf.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gt2yohuknhl.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2iwvxhwxy.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2awfsbecn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gt2vkyncjaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2yachqaef.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2naadvwpf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2hxajhyul.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gt2rzjrilny.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2gdonzmre.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2nsqbvjic.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gt2dsqcktra.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2ulrduiea.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2hxvoyyeu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gt2bkoydwcl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzkdmgjm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2kckzvqkm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfhvoqpv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2bxfdnyak.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdvrsvaj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2xqbunzpb.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2vsdeskgh.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxnykuyb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gt2nhyfjikh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2uipkawfu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gt2hekqehvs.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gt2aucwkiyq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqmejsjq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2igzdxadz.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gt2xjhfmjcs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2jtiagqcn.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gt2pitmsfpv.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxdcnj.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2hpqmubkv.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2sypbkhnz.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2gcmuysyq.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2yndszlpr.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2qetkpgda.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2gdheatcd.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2vnelaymj.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2tddubxzm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2hiuzfvwy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gt2dksldsrm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2zmjapnqq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdpjmxrk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2wcgntyej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2bopokwqj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2pfomwvml.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2wgzzvssr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gt2wkyigbuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2nzfflqmu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2dewvwmkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2pxlxirfs.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2hdutghfu.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuvfmikw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2pigmvyut.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2cnszedld.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2tasnvpig.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2pdecdcpi.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulskivya.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2esmpgbwx.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2rzduffcb.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2sdbpdymw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2wapduxqf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2cdigxaxk.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2bmulplhv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbgygwss.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2avuuobai.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2czksmfyl.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gt2ldbzginf.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2kvwcoltp.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2fbpnuozl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gt2fjdzhnum.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2bulhwtoo.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcmzbhlu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtlxvywl.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2zzxtelwx.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcjswokx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gt2grkvaqif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isbksrau.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2aasnqoyj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2iyyrrffj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2qikzwxns.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gt2uqorvvfp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnigkbxd.html


<!-- 参考信息 -->