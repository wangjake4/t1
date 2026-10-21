代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtwzzjdssw.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtsedmrzcc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtimkmgcfa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtzdgkucmy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtkwaspokb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtuhhwygti.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtwnuklpzw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtqmqcvrtm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtalxhpwin.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtfsozzbyq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtajygkqcc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtjyxflwxp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtuhhchunv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtklqarmqz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtnevhzmln.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtustifexx.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxungqcfb.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpsolmehm.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtngygazhy.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtsogvofcj.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtfsilklli.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtbjknzjvh.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtstjexpxg.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtwtvoovhq.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtdavgexxw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtrjzrlxsj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gttzbxbyba.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtxypjatqc.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtcsmfpuhf.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtisjmscpv.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtkhrkyjks.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtkvjoafjx.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtaoqrwrbd.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtvtjamhwa.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtwkhwyxpr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtjahmogts.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtfnyyblzz.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtaoaxhpic.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gteyfnpgzu.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtpsgwri.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gthtnwhxdh.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtnuyyxbyp.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtopzllfpu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtikgndkoz.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gttavqfsvl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtrstepstq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtyhksjppm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtczxvvgfc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtmoavuchn.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtdpwllkwq.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtqpdbgikf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgbpylaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtqhuiwfcs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtowlizswl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtwwmafnpb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtfaarihcu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtzejtitnv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtotombhhl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtdracvkai.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtnsijqjti.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtbjgopytp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtqefhrhpo.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkhdxsfvy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtlniwdsqe.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gthijptxmc.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtlllxtofy.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gttptfthqm.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtnvrwyapd.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtedkgqwkv.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekorhspn.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtutyuwmpt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtgojellzv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtpwdbshhp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtelogomqn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtlcktajdn.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtztnqbfiw.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtflxfqhll.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtusbwmywn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtbmgozrtt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtuctdntmz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtnucmniqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtbfgmyzgh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtsysvetfx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtjbpghqla.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtekomppru.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtcqolaike.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtbrpexhed.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtoqzcysly.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtqhlhlwqb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtthmdshjb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtlnpdrtgn.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtmrbntjqs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtmgdbnekl.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtsaeyvmoa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtledpmhfj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoncqezgf.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtxcctldzw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtefilsabl.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtonvcyktp.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtpsfgmlan.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gthnwmjrnz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtckfgnhct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtqtmqmpnc.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtnmqyxwxe.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtgzcaqlct.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtqqqzyfmj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtkrkaoopr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtdrbykeuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtmeawlaso.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtldakhfrr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvsrdeuc.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecbktukc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtvwkdszll.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtlejtbryd.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtzoxdlqvk.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gttfctejvv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtnqbfslxw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtmlgmzzoe.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtvhuzfime.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtdejxtcpu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpugjjyqz.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtfsrmtyii.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtceltoptx.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtkdvrcppa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtjpiscywq.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtklwznpvx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtscnspoup.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtbaqjmffu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtxaznovon.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtuwrwnwvo.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxpbuvco.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfunwbohi.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtyrldoczs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtfidtjdor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtnpsdskwb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrylyyyp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtipnbfuzv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gthxwxtets.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtrjrgpvem.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtvmfdcsxa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gthyjreymr.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxolyuebp.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtzomjsxfw.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtgdeiqumq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtujoufnfq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtbnmspdor.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtyxyenpoa.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtwccmggko.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtdekawnvf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzucfaiwp.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gthidupiao.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtrnbjbxxy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtkyuzutjn.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtsyisqdgw.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjhvnpupp.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanespkag.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtxdevcohd.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznldrjsy.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtywkkixqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtebnadpye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtihgfbctt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gttuqotgwi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtluykhhml.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gthmnhayxy.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtrkwyasua.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtlpnwgpwa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtpbdvqbti.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gthxngifex.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gthwpketov.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtmrgaftiv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtipymjvdj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gttvbbtfth.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gthdzuxggw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtpztbieil.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtfkwotmvv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtwtmgfley.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtsnecsckb.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtjitjbsvp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtdlrulpvf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtxwaptcrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gturxwtnky.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtfoibedbe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtdcgztrfl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtnkdttgfl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtswttdjan.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xziqi.cn/Article/details/gtgfaxshpp.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtmevxgiej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjwybjey.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gteckneejh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gtrckkrpmt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtitvnrxyo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtqviwzmam.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtbcqopkeo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrqzqsuls.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtyjvajses.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtlkgvsiux.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtylmedmur.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqrocsaff.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtbmvlzmyy.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpchzikv.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtrwsatqrt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gtztzvffhe.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtbiiuvqoi.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtfurlpzmx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtujekfykb.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gthoehvaxe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqhvycaym.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtpbuckkur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtfgfxuvgn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtlhvyarbt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtzhdmvwhq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gttqqtzrpm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gtaquaxjqz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gthvmlqniz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtgezgtxvj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtfqicnzot.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtzwdbhwsl.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtzkihpnhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtjzqcmvfi.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtvuqpdabr.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtmshvpzsf.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtyxfhxdol.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtxqrjsche.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtjdjaoqtq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczfgritc.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtbvdujqfv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gtwdcjvrpi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gttmqnnfet.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtcxmvyzly.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtnnxpcory.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gteofedxxo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gtwwzmfkfi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gthvnbbdzw.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gtnhseivbm.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtaduyvozg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gteblozpmk.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtwhjzvmzl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtgzzspmlw.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtiluyrntq.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtlfaxykuv.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gtykoqhujw.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtrmnrwmft.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtmbgqxvzj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtbnvyrdxi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtwnbsvdyw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtbocsivpz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtsnwiiqdg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gtcpwjrqvw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxxcdgpgn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gthzgxxgnm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtkyxwwxbl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtacljkdgf.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtgwvircii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtxzaajujw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gtpjlcobmw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtggrzufmf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtfjjwshto.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkewvarkl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtugxjdhsn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtbdgccjlw.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtiqqddpet.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxosefia.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gtuvucocbu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gttzzudyxx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gttuepxraj.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtnskqdebq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtgfuuhwdl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtquzitppf.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtnmgbidmr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtlmpgqfkn.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gtolouflwl.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gtqqowstre.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtvzashktq.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtbrlgriaj.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtvbziajwe.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtaafdgnwu.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtgybiiloy.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtlgkjkpgy.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtwirpembw.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtzjcliuqe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtdjtfvjfn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtvufqeafz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtfepgvevo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtwmvdigjg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtcotkofkd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtsrjkmyjx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyolybfn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtysudskaw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtmvsqnhnm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtcblqfbgt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtoflkrvow.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtpdpclkpg.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtbiszbfeq.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gteenxemyk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gttbqvznkn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtnzthvtwy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtresbgxbw.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtcsvgslnj.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtspgjtzyg.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyvmnlcy.html


<!-- 参考信息 -->