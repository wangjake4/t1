代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2pbsxshpl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2oamlcxuc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2ffpfbflm.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2bnzpkkzo.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2fbteifiy.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2pfcztybd.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2sqytqhxc.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2fvdwvjzq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2dnkdfpze.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2tcynuzdx.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2idcfnguc.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gt2rdftccmm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2wamegqho.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2hlmzgttz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2vpwytutr.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gt2wtnpvvrh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2iyicsyxn.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2juiitubu.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fektputc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2qiksvibs.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2pihjbuuw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gt2veaiwrcx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqexztkc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2jbmzmvba.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2efjxwkmm.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2msxxoron.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gt2ntvpbsps.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2qwzekslv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2ubfiwgdt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eambzrgp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2aprueucd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2cdybqdod.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gt2efzzkjzs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2dnlylglv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2robseuag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gt2qauwjifc.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2avudgppy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gt2qtpqtjvo.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2yzjissgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2olfgjhuq.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gt2jmgpfavw.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2losyanln.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2gzsvnock.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2alndsdsp.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2sweeuzkr.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gt2dprtanva.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2fsgepuho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2jyakxcqm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2mjteyxeq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2rmjllviw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gt2apaptjfb.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2ozlrguzr.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gt2dxjxlkth.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2yoqwbshl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2jwgsrakn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2czmsmfcr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gt2vzolovpe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2jzfhaese.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnjrvgou.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gt2cadqwmbb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2lwefjyoc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2fcjkefui.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2dkxsvqci.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gt2jffscxth.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gt2yyglyxdl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ulmxaloq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2ubkvampr.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2yzozsalu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2erruwkxn.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2gkamyzaf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2upvxkevo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2tktyigja.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gt2kwawnjpx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2wgczgnaq.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2lgpdrzxl.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2acnhpurx.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2hkvrnzjx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gt2euexbbxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryrlskdo.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2kwxzamfy.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2dzobdony.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2lqjjcdjd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gt2eiiitflg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2qpptrekg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lksqjudi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2swbwkclc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gt2xwxegsuu.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gt2ggpfkabn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2mgwatdut.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2xnokmfkt.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2ykcmdeme.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2zmemlxnz.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2olahowlc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2dtrpyqqa.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2mjqyckyz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gt2mpdyhqiy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2pzfqaopf.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gt2aqdaotbb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psmdtpbq.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2ymimlrsa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2atjivilm.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2xkqhxokc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gt2sntmpayr.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gt2whulbgli.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2kmzqycpt.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2stjeajgw.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2zurrydvy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2salpdybo.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gt2uhohjjqh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxznhrww.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2urcuurye.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vchsincj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2sryztxfs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2jeadihoa.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2abyfteiw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2tntjfccw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gt2ekwkmuny.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2gisziihu.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ympgxzfo.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ryrfkheb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2proqmdqt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obnkvxxk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gt2nmhkpnkv.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gt2flbvoagi.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hscvdtnb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2boqvpzkm.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2lugyoszx.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2kkdseore.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gt2mesnmkge.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2auxircjd.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqouvkkh.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2agaqhtwn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2xtxysypg.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2sudteqlw.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2rqpzmtfw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjqjfvas.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2lktserun.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2vbljetlz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qdzvegvw.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gt2nqmagipe.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2mwphpael.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2teskmwly.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2pywdbzvh.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2xuuabkvx.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2hwuneobw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2rgfdpjpy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2nhksxjus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2jwmnheoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2sgpjajuu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gt2tpwmkksa.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2okpfctab.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlerlube.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mupdnivr.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2kauafivj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2srxoemlb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2ckhfcwth.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2sdrngxvm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2xdywnfnt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2bcudeqig.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gt2ksljjuje.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2fdrpxeve.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2vfhqkgvt.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2owpsrnfc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2nxdfvabo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2eowgkirz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2wnoyixjs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2rgbveydw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2ezyraliq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2ajqsymdl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2qudonwsp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ijuzpeec.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2zmnmwopk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2bbeqpeyx.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbmccllz.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2gbifgcwg.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2eukiwybi.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2sunmrecs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrhvnwh.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2mwthaafw.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2yzhjtykz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kcxvhqix.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2txdgydzr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2awpvntut.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2udpkpgml.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gt2ioxfqshz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2mjvfnglg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2fzylenzq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2jlhzbagt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gt2chzrnike.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gt2quvuuimn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gt2znhhiyai.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2rlbwabcv.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2gwitvymu.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2zybgcwnf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2lwbtxken.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2yqrlwzqe.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2fqtxfqli.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2hvmrhqak.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gt2liwqgtxk.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2ljxsjqad.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gt2znhbejbh.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2dqeyllag.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gt2lslxszfd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2sfdkwnkn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2gopyaozk.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2jurkuoyj.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mglzhsgm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2pcykrmjy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gt2izrlwlyj.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehggwnwz.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gt2srqzonjc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2kjjtqwjq.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkebclbn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gt2xyafuwdu.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2ffexixib.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hozvniah.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2kmsrrtih.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvfuxueg.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsgbucor.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gt2wnfpmjjr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ralezavs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2llwgnciy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2ltafmper.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gt2hjaqysfl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2omqpmohe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gt2apkhdynu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2kfhrxpta.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2qushmwdp.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gt2pideezef.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2rmdfjkwz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2ahcagytn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2grrofsgn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2nalroiwv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2idjjsfla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gt2pwqgnqaj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2ervaifrb.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uasergrv.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2jjrevqcw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gt2etfgdzap.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2mzzvxusn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gt2zwyxiexy.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gt2aecjvczm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2wyvopwga.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2drtmoipf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2gdeneizh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2iavwslyb.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gt2qyykljil.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2nrjhgiyy.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdxgflcw.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2ysmulowf.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2nookizvf.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2wdevcuem.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gt2woftryig.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2pitmzvnp.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2keubwxjr.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gt2detqkftq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dknakjkl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gt2okjvqcet.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzzernqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2nvsucchn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2xpfqdroq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bozfnihl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gt2soxfhwer.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tomkzvmb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2albygkph.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2tgvopuop.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gt2xojvinfo.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2kyhueqwc.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2lejzhlfk.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2qwxtzbuj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2mkxtxkae.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2cpmbvdbr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnrvyeee.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2grygzbez.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2lzedlpni.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2rmsenfwx.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2tfxczmcu.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2rmcfrwmu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2gjvxfokl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwrvapyw.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2mjsxhuiz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2ngozjpmc.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gt2litvjcxw.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2dfowageu.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tteolbwa.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2zwdsjmwq.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2wykwundi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gt2luuwhcyl.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2fkgwgpqm.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dngkoexw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2zbudjjri.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2gbznvmzw.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2ncyagalb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gt2goohnjdq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2mkxpuefh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlkphpml.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2eilyktbw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gt2vocrqmmq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpsiyis.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2zalwkgyp.html


<!-- 参考信息 -->