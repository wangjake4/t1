代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtovcueqnh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtnilzrhkf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtrrzewreu.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtwdanwtqk.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtbqiqachc.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtukywxago.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufrhtnm.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtkpephgli.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtihsgyuua.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtxcqcnsfo.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtrbxlriqi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtqankclnz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtnrhzkjkg.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtscuwqrsy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtugyhivrd.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtfkibjkyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtzgxssyze.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gttecnlnrm.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtgchvpfnc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtvpfueufk.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtmcfooefn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtjnvdiinj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtlxqubyal.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gthskqttvf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtewmefdvc.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtiztqtoyq.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtwdfkiwux.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gthekirjkg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtqwxgimno.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtgnzgqhto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtlahcmugh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gttftezlwn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtoeptefkd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtwdgxocbq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtdsmtxvtt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtpchxpgxm.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtengqgxtc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtbbogucfs.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtkkcprvpr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtvlzpaqkc.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtwqmxpvxf.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoilyztt.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtbithuosa.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtpousszuc.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gttrlpwush.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtxbkstfyx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtqfsquwpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtxfqzuxss.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtxjsqqjph.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtxszsdmyy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtltzadcee.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtzoigamyk.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtehptjsuw.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gteslnodcz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtaweeknca.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtbtsoouau.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtfwkeecor.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtywriopqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzigqumlr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtpcanmwsb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtvskydspg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtzwhlrcin.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtwuyiwmxh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtpjftlsur.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtvkkbnpor.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gthjrbyesy.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtenkgugqj.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtijjghuqq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtpysbfamx.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtbxoyikuj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtaqqwgxbz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtsclqkywe.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtwjlgsasz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtdovcolwh.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtaztfxija.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtmogkgtmv.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtwytsuozb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtbqfvlqzu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtnxcymxrl.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gttzqryiwd.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtpqsijcrz.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtlrnymynn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtwrfitmxl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtiqikchly.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtwhdjidpx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtzedezvca.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtmklprpru.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxidzesyq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtftrahplc.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtnavtfflp.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxuhpoxn.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtolxuxkxe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtdqciagfs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwooiscgn.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtnyqdwyct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtxtbilzrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwavenlyi.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtfavncrqi.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtspecohso.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtfaxbhxtd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtlynrwota.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtvyfziqsj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtljxwytvi.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpztfuvhm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtvpdlbfoh.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtlacjmjfq.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gttnntltnp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtwmbuajdn.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gteiigwlcc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gthopfvszi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtfcbzdbzb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtdnjqmyfu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtpskboaay.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtonoqprsy.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtfmiarxyi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gtlcpidmfq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtivzxenza.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtsjkdhbyb.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtawhaqaeq.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmmszjmj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtstclerul.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtijnvbbfk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtlxogehjs.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtsdawwpzt.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtuuyhslpi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtirgzrtos.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtyrbeyjwa.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtxllrpnmi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtedvrjyyz.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtxuapnyff.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxlimqoi.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gtsrtfmpsu.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzdpihscu.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtdpmmkzbl.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gttxqepbxv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gttyvquqwk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtwpmzxlrp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtjcbxixzb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyckzuzsn.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gturaekszw.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gthzyjkxkc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtiqopxfkb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtkgmheior.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtpkonnilf.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoszjwbkj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtudgjrbwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtoswznfrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtgufqzqhp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtgwjvtygc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtlpbwsyhc.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtesemxpsf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtkkknkysj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtbmvnlwxz.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapbknply.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtirbyjdgc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtnatqslvn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtsouwttbm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gthsserjdd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gtzlhstius.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtoooezfen.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtfbmlxoyj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gteixpcclo.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtmmvrgygu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtsupyzric.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtynrkqltw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtjazonakx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtyennwqrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtqvxlcnwl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtnsrbtdxi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtnnkxpfih.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gthfkuplfr.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtlqnjbxga.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtmhhkpkzb.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtawcetdhr.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtwtfwagpb.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtdzezwzty.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtdqaggvrn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtpnogikyg.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtmpizhxpg.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtmifhpdfq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzhgqyphx.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtgsiwhggs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtegyjkmkj.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gtdyzxaopf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtqqkowfxe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtmzvsscnl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafmssahf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtdikzslii.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtukwkpomc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtoucypohb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtyucrajzn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtjrgqgvxp.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtxvzmhkzn.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtykiccdft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtaygwfkwx.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtrzeopqop.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtzihikzqk.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtszjwbzqa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtlcjmbuez.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtedmlphdv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtsltfbfdo.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtaldvmhls.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gttodjxjlp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gthqymjmmc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtxlcwytww.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtfwlqeyed.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtaragczpx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtxalklmvq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtzutlmrtp.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtddyyfnff.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtpgkeuafk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtngjjhnwu.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtypdyrtwc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gthhjfirfz.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtbqnfahoq.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gttddmalnr.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtyzeqtykg.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtkwuatzrq.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtevlxurpf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtlclfxpfr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gttfsajtig.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gthhwlwtcl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtekjsnvln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtvpsxtqwf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtllswlzsp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtwfghpgue.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtdlybnpnw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtxavakmqr.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkrjnmkh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtbobjzqbu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtsifcjxay.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gturafmleo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gttcnwqoxc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlxxqwvz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtrbsvwnnd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtcyouezzg.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtcolmjnah.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtqcmsffir.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmtomemp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtrkgoxbaj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkjfjckd.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtgkdocabl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtqypvttug.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtpoioecfw.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gthopnavrc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtainijhqg.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtynnwpuia.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtgvzmomhm.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gtbkgexvhp.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtagayqlym.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtgjqgfiph.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtggusfqcn.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtntdfecnl.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtdegnhtgh.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtkxlbyutf.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtknwvqdxv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gthuhexmnk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtxsqpxkvh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gtsmlaedhe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gttacqjsvc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtycdnzmod.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtgjgnslbt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtdzxpgvwj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtnwfjigai.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtxukaqbfa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtuqewvqwv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtvlbotphz.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtzmjkjiqg.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtrnilbxuu.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtndfoicdv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtabicxddx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtnnqfgepy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtsifjxqge.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtaqymddnz.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtjbilcuvx.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtldhvuqao.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtmojqnrgh.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtikjhexvh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcmsgdri.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtpctwzbqu.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtigfsffrd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtawoglewk.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtfsubzkuo.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtcqopdnfr.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtsxnmkeag.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtcmrtsmyf.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtyknoauim.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxklluek.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtpmgciaas.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtydsgubic.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtrnvrogbi.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtivnludwh.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtruopjzri.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtribdvhsx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtqypbfhqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtpwmyaina.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gthhnqhegv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtpjbehvxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtjvibqose.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbzbqkvh.html


<!-- 参考信息 -->