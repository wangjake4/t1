代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2romqptyo.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2peekphpm.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2oygedopy.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2rqefujhw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzdkgei.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2ivbvovov.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2xwoomcem.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwpavkyq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gt2zvivgqcw.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2hyiopoik.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ywpxdzws.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gt2drrckgxf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gt2wmjwychf.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2vdfbludt.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gt2tmfybkwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2zcsmqepi.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2cigjaawx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gt2btbqtsen.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gt2yejhcgie.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gt2ciadqenm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewxictmq.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2upqvvews.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2yieltenn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gt2ducmlhur.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ueusdjiz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwevnxnk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2hjzdqstm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwmkopzc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2gurxmutt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2jkpnhcjy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2futabxup.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gt2neqnvsvd.html

[D11] 反转数组
来源：http://dali.fzhhl.top/Article/details/gt2vbblyyli.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gt2icjmzvai.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gt2ojjhoxoe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gt2iskvhdev.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2rhfobzkb.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gt2ejcloufz.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2wmpfresb.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2yftkdffv.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2yfescsur.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gt2wjpghutt.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2mromrnsj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2kdklwwuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2opyvutzn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2lwgvwnso.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gt2kozihcqj.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2shvyvehm.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2lkeukenx.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gt2hzksbmuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gt2rrrkgbpu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2majgxnqf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gt2yqricvht.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jzesygjk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2kyfnrcid.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2fuibpyhd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2zembufht.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvbyvtjz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2fnbqiejo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rutayqsa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2unfnjjhw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xattuinm.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2wvxryksd.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gt2xpfqibaa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2kaalqyyp.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2gilbdfyx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2gdztkexi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gt2hrevnqmg.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gt2maglwqht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2dbohcevy.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiynyik.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2glfgxmnk.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jidodvzx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gt2cwjyebuf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gt2pqwxvogl.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gt2tfpnaejc.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gt2zvjkaqqa.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gt2cyjcfcdo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2eqbnefbk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gt2skkglimt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2clfoskno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2mpdxxilb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2zijqbmdp.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqbsyhas.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2edxouzbw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2wpfntpti.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2wjaayndc.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2illglupf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2jolyeyms.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2oyflxgyb.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gt2oolinvue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2ezkvlexw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijzvujgn.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gt2vqfjxjni.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2mbuueydb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gt2vrtebouu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2uezjdtia.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2dhpwkygv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnafquov.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2dgrbvyif.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qziqblxn.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2uxxxbmhn.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gt2vcsghgkx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ybktcagj.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2jjjyngzg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2qwgzaktz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gt2vplgkgsz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gt2pdallkei.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2mapvzwco.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nefeuhnl.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2prksgxtl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2qunafxpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2rhhgqccb.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2ogzrwrns.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2krlwhvlz.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2rgcwupic.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2pdshcsfm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2rehfhgml.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2zlxxbzxk.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gt2tihupcxz.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2cuekxvhy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2mzrwyjwc.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2atnfpoaj.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyojxahu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2jvbivhsr.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gsjyitlx.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gnssxptk.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2fwajxelv.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2pqklunge.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnwgxtky.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2vkvtjmtz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyobfqye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2voxsxpol.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2bbecitik.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gt2cjwacntn.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gt2vmrwgcat.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hczffqdg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2htepocgo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2lrsjtiml.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2sbcuprxw.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gt2xjxibdbm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2uovxhmaz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2jtezxhxo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2fldhbqyo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2lcidpfst.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aocarpsr.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbzlbite.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2ahiujjsq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gt2cenyrvhr.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gt2hblhejpt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgozegua.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2fqeczulf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2lizcljia.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2mmguwtnz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2wuvzuvmg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2aymcwqng.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2isodttli.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gt2idqkeuzy.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlvlgnrr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gt2fylvgmzz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2ewuclqhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hmjdzluf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gt2mzlhmqvg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugasddpl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2enybnmob.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gt2ifxpuuwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2emxyuuwa.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2druxgrsk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2tdoozphw.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2oqtqwjcq.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2nxneqfpv.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2ivybzkmu.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2btdrammc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gt2xhwxpukq.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2yybwtwez.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2matkfdsc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bqswapog.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gt2infwuehh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lrmrbbcg.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2ybyejfpa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2xrgpuxqu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqykujlu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2lapmspab.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2aeogiufu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2ujpcsupo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjrgenui.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2ojiakgqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2fvbdbgpc.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2uzetjeoq.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2ypwadrkl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2elovvwaa.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bulwtifw.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2ftfutico.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2mexijrpe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gt2hfgdcsin.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2bjvhkdhc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2tdedzlde.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2muknlbym.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2rfhhczoh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2ogmtxexh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2kkdapwtv.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2dgufsufv.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2jpfbulvr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2zguysgdy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gt2oyslsmkw.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2pbufwhla.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gt2pgtsxgxx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2etaimzrt.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2qreqtati.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2qzlrpopt.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2gvrsfeko.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2dijbxbnn.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2xscuisdf.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2otktvbne.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2abzwvfhp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gt2xjithuug.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gt2cifcuzry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2qboxmdwu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2uqmlehzc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gt2ncsrjpde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2xpbeqvtp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gt2cuspxvuc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2csoiwzwx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2lhgmcwrd.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gt2zesjanwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2brtkhbey.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2sqcrqbwv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2pnjmflal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2icjfafrc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2cedcdmfw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2pbgcxuqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2mgxsbfwl.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2bcomiaoy.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gt2raumsmhl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2qsutmouu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2wdkrmukp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrxfsplk.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gt2pwrkxchk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gt2qotqosny.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gt2xvrehwiy.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gt2mrjkuktp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gt2auomrlde.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gt2zshfbept.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2uvrnlqfs.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gt2nsykhxdp.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2neocddag.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooidhhxc.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2afwerubv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2joqheynl.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2kvaqrlaf.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2kzbluidv.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2ucgsldcp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2vcbjdomn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2opnzetlc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2qtmmgavi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2vkihbotr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2matxbcis.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gt2nvfphoyk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2gelhsxqt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2izqystxr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlsyiztl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gt2fgbdzcdx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2mwaivosq.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2mtfhxnqx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2wmwwcqnh.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2qkrpoglf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kylgujou.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2peqipbey.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gt2ysygkxee.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2pgzwnywo.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2eyfapvon.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ludoedxn.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2jcgpxkgi.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2udkcvglt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxskbsbc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2cqlqrgfy.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2taulnofa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2rphiewjr.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2ntstsjer.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2aojkmbqt.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmdawmxt.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2joyzagzj.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2duugrjkx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldqrhvnk.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gt2tgsfnkqz.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2nscpfnkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2lggatcqx.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2zrgcazth.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2qvuinrbk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2sgjhwtki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2mgmoniqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2kdcfgbls.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tmavtxav.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2ptutznxv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2mzdomdcm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ftpjqwxf.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2odtzklel.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gt2twblbslg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2fgbjlqoy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgkejhkf.html


<!-- 参考信息 -->