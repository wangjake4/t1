代发 wailian999

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtiitywyoz.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtntgjziio.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtbpiinvwx.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtvbcvwcpi.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtxyrrkrcq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtfmtlbhtc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtcujxexqb.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gttiqbsdij.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtoldqiooa.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtlqdcobie.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtsqwvbmlr.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtmagswhjy.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtzprnukjw.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtclmzkkue.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtgusbbvjw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtwsxlnlfh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtukpwvbdn.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtamaiphlm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtgsynitkk.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtvwdxxedv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtnxlvcful.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gtaonjdegh.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gturldbubk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtqgqfclni.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtgmxrbkqm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtmivgwyom.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtsavqihuo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtrukxzxni.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtfdfjsijo.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtpeouigzv.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtpebdtzoq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtmzmpidmk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtnnsgqyvm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtlwktkhgc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtpzaxgqwi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtkwpvqcvg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtgkfpqqta.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuqkbckd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtfsxwkdun.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtrkaniebq.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtmtlqglys.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtjkntcqze.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtahrbamch.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtydgyoggr.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtsmjjynij.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtraticemg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgcalyzfi.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtxcxglyxk.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtycgszdna.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtjckbjroi.html

Py:   arr.index(x);  x in arr
来源：http://dali.sweek.top/Article/details/gtnybmqskh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtxanvamvv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtktoxejcj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtuwsnxzmj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuhlollu.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtzmyhvnly.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtskzhghbp.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtrryjiwui.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtsmafjupo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gthxylkxhv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtjjxpgfeb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtszcrrbtl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtvtnqfuiw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtgtyljcjx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtsqflzrhh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtfdhzrwlp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtsukfbnbx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtrypsdgcl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmyvvkiu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtziacxecq.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtgbbawpcd.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtquhazamk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmpxnrvoi.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtdjwwzymg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtuecewlcz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtkomwykcb.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtrfsmmnel.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtqytsfpno.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtmkkjumka.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtikxokhyq.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtmfvxnuyy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoloiuydh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtnddapnqw.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gthwipqzqh.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtxmqkkptd.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtttwycttf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gtbfjrgios.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtiicocxjg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtkfokkiip.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtzhwykvho.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtuzmxqpov.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gttfjvowma.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtbanfthrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtzngjfnbr.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtewdupklg.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtfczudqab.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtpnknslyj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpreenva.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtxrzbnymg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gttjpvrxnj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtdyzwckvl.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtpokfyqoy.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtpmzxicgn.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtfldbyaaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtxlasspwd.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtymxkmfho.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtiwfoigck.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtezpklnhv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtizlrzqao.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtftwwriie.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtjzkwcovv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtduujlqig.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtjfnvxelw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gtfrowgseo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtaphxlfzh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtzsqbmeui.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtsdhicava.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtzwbdgose.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtevvrxuty.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefejoidh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtloyfaqtd.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtbhroljmi.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gtxkhkbxmu.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuiccnkq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gttwuxywsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gttupzhrgf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtlnxjitdi.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtcvleigvm.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtevdcsbjf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gttggcboge.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtixxmvtqz.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtrwirlrmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthehcaywh.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtlrzcjfes.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtfgtypubm.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gtcrdezdwv.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtmyahgime.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjnkcttbc.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtxsgbsnbn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gttwjzkzgz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtxcixkdwc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtehzmptwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwhloagl.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtinnavvll.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuphrrti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtqxurcbnv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtwhnhhuml.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtzzfsboix.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtrodxqnif.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtsnjjmpov.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtynbjwjvi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtyckyeuih.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtliwdpnzw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtyyzthnjp.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtojnbsrbb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtnqqrfmyj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtfrklvyva.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtbkwyzsqn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtgafzgmuj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtprzfshcd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtfhzkzhvv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtzkmwggmt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtjizvceru.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtrqzaitfi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtrwzcrwqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gtsppaqkiq.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtnsbsoygo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtiztnvmij.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtrfgcmtwx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtsmhlahrd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtjhdpfgzm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtsihzljmv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtowhlodfy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtvuyuhwhv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtbxtpeauo.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtmfqihevk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gteztytcjx.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtsilcuhjg.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtfwywqamv.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtdgyxhrnn.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtzdahikhh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtbgphctyg.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtbwbvsjqv.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtjlwomtea.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtedmxvuvf.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtstghlkeg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkvsvfdgu.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtatdmxpal.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gteprrqtli.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtgxrphnjy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtcmbvqiuo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhowgpwb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtqwpkjnru.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtutvuaovv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtqwodmwry.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtxisecnju.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtktrfeemd.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtrtpdlgzg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtfnaflunu.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmuuegoj.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gttweiswtp.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtlmplkvga.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtudliahwy.html

Ruby: "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfgmssqq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtsejhgtiu.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtrtsdhvae.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258888.top/Article/details/gtaxyastnr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtzozfzdlr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtdvjzffqh.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtpvlbhqtj.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtbpvewcia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtograjkmm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybewixii.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtklvehqeq.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtqpjlmshr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtyouwmazl.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtnmkulsva.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gttjubiile.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtgrfxntot.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gthkcuskvg.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtzogzqmeb.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtitnngivx.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtynkjauwk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtwnavqiez.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtjiqaxtiv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gthvhvfwec.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtskdgnwlg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfddbsnl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtfsjzrhhb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtmhwcuhua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtmhqcthbh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtuegkrben.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gttepalrij.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtlibcwqgy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtlevzwrqa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtrrmrtird.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtvcldygfd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtgdqcoptk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtzwkddeoz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtjlwllrgx.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtpqkbdazr.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtqisbmocc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpufbfswh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflfkfyda.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtveywqhxg.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gtacwngazu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtwlvouuxw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gttvbouelu.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtevcgvsht.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtezxorexe.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtobsgwsqe.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtjjbcpmle.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtvzaukuum.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtkrgdstxu.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtkfvemwcz.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtbbpiqszl.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gtflwkrmvr.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gteszsyzsx.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtuzottyvh.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtjnbwtxgi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtssenvyap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtahvjssgz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtxsslpgyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtoufchmqd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtozkyahwg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtprnadhfm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthozihfxm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtaxvgmmns.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtbynwyykr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtmqgoepst.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtembyujha.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtngyiqrhe.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdfkrezfd.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtjwnwsjgc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtwpxcltbf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtfhupocee.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtqwxefjmp.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gttqocyahb.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtoallobiq.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtklckimoh.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtvkaeszfh.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtcryqhmsg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtqrnffedh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtboswxqxj.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gtvwnwwjfc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gthqyizlap.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtagkvxthm.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gttufznhyb.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtlzvhmglf.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtupknpape.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtpxnvahpl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtyxohlacd.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtlfndzaed.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtgfodnhja.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtrwhhxagc.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtvjpsqvli.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtyiswumid.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtspkpsmxl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtiktemlcy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtqgtprvio.html


<!-- 参考信息 -->