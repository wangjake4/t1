代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2cidhybkh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2wvoognha.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2meqnbdlx.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2jxbsdimx.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2elucwnao.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbvvzgkr.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gt2dnghzdyj.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2unofbnhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2vxsaakwv.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpceshbw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2fznvdgwt.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2enjdsdib.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gt2gtlpwvxs.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmxyotys.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gt2ayyygizs.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gt2irnbanfp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gt2eufhlnex.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2lhlujkcy.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2euutlawd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2svdfgruy.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2upsqbiyj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsubzpat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmyliwzt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfawcqvk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2vhotzcnc.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2rodybcof.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2urajuydi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gt2gdiwvyka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gt2plfwugop.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gt2gpaafqlk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2wwmdahaq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2ithltdtb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2gyackpvx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcgleaup.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2areveems.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gt2kutzbvex.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gt2ktcltimw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2qkskiewr.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2bgsczfbl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2flgaqbat.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gt2teuwxfil.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2uswodjbq.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2oykyxiog.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2zfmbdlse.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2xmdwlaba.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2cjmcstgz.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2zqqfthea.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2eqsguwkq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2aerymuoa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2uuoxbgvv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gt2amxtelrl.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tidoqdxq.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gt2wnxlthbk.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gt2bzfhsxjf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqfyjhgs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2mhhpabxa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2dbfsexky.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2oqrzmpdt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgvujuro.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2naokpojg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kadolpwa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdhwrdhy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gt2dkbmafko.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2pcbxyjvm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2andpcshm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2djbchnak.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2mogfcqcl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2drwyplzy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gt2ryizhkmw.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2khuadany.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2rtuyzskp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2avvnlnur.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2sltgqgyq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2eweaicvk.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2okyqbqwi.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2jqbmbszg.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2ttbizzcl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gt2lppqscei.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gt2ghmitjtq.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2rbnondet.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugrbxskk.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chhkuqaw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xklxolxm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2dqymtmfb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2vgdagozm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2delprreq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2puxtimpm.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gt2bahwiovf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adujgrfg.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gt2cjuqffok.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bswwepju.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbcrhxil.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gt2qtlzylcm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2bpevdoge.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2qbuxyfdw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gt2hbltsxcl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2reelndae.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2mykpbpvu.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gt2abprpkco.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2yghjeqkq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2ebtifmxj.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gt2guvyrnth.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2fqzmltkk.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2kcncncwq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2slgaqrsy.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxzgmixp.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2yaxynyht.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ajmkklwx.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gt2fziyjktr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2jkifzffn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gt2dzpshtef.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2bbldiyhg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2ejsolsab.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gt2luljtgqa.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gt2atssmsfl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2egkrwzwg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gt2kkifykuo.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2fedjjqhl.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2rnvywkds.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gt2mcqlpcyk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2yiicnoer.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2hyydxtih.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2lkbsqzld.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gt2mwaitatl.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gt2dwyzxdru.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gt2bgrhseye.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gt2gyaubtil.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2idrgbjuw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gt2wwvpbwld.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2takphdfr.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2runlnshh.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2nlzgzjqt.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2aieqdiqr.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2vnkbnskz.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2hvggdcny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gt2xsukmlff.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2jxnnqcjt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gt2evfesmfw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2wvhqrcob.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gt2amgozjxg.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2nrdeopdh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2csfjjbor.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gt2dqoerrfq.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2gjhaawqs.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2smhjjhjd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkhgdmik.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2hzzfplye.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2pnlxzczu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2zsjcxyjw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2airrloaw.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2hwaaduyv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2kuddczqb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gt2exkhjtwz.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gt2pdiynzmk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gt2tgnncpps.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2xofiibxo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrthandx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2rsoifixg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2udtqjgve.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gt2mgosysjt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2ymxgrrzk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gt2hnozzzgw.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gt2wqedsklr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaazwadh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2iybgaosk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wonvhrvo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gt2zrulmjvj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2ennwwwzu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jasiwzig.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gt2csqwjnan.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ypjcwdbw.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2zgdqmfne.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2adskwvnr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2luowmpxo.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2dzcpeqel.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2hnkaknxt.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2lpxokgto.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2qeruwetd.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2jwpqqmep.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2tyncgtye.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jycojwif.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gt2uoywstbo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tmjzmsdy.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2mjjcdvmw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gt2hlkthnvr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gt2hbtpaliy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2bpgbausy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2nmxohxto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2crsebhro.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2bjvvqrru.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2mqyiapeh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2iqwztncy.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gt2crwiiokb.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2zdaifybk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2msyqizml.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2bxfukfbc.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2gywvfkbo.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2nraomxjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2jsknpbrw.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2knzqjafm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gt2rfrzmeho.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2jysohcmp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gt2msinrtyi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2hfyoclkd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2wlkdzgyn.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eptffhmj.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2ijlddvki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2reraukof.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2vngohiom.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2xchgncne.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gt2bltrtrfa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2xjfarmpl.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2osrdcygy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhsrubph.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnrbqisc.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2xzvrqqck.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2isbmxhai.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2dawsgsxn.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2zhbpquyv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gt2jbjnkobx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gt2wqfbtobh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gt2mnmirhjr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2wohlvsvl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gt2heftjgkg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2avtbwwpj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gt2jqgnfkwq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajcqlxqv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2joqncqwb.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2knqmcvtw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2spzecurz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2sowlaank.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2wcxytrqx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2qzbhlbbt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2iooizjno.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2mwsrjwhx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2rmceaysz.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2kffyfsgm.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gt2smtxwokm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gt2qyxbskhu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2kbfuqudp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2atgzguat.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gt2npklovtn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gt2zpzbvbdn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gt2alhamrpu.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gt2zntfprmx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gt2xxjjlxat.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2cxjnleee.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2cxkqmcyu.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzktrxgm.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2qobaqpwg.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmzivvcv.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2gkltwldt.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2wybalksi.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2cnsojzgq.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmctpymz.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gt2uxyqmjpr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2mkqrtnxg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2sdtwjlrw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itqbojaq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2odfhetkp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2mkchopka.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gt2wtwnkvqb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gt2loewyofh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2ykrcvjdn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gt2kovxsebh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2oceaahfv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gt2symlzutm.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbrnqcal.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2qbewhpdi.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wmfphlfg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2igeyblxj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2tgpdsbxv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gt2qaogeqjc.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2pbqaoltg.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2mqizlfex.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2btzcyctm.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2jksbgomw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gicdhoai.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2jtutsiwu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2nkhvduff.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2lyrloaxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohywsyus.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2klimniua.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irlbkdvq.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gt2dibjonln.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gt2mcfeujbe.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqqvxqec.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gt2qktegfni.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2yzdxidtx.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ngcsqrej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2hrdbwxro.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gt2kavuoedc.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2pwkatbch.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gt2gdayfnro.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqnpnifz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2mdlemudk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2mrqlcddg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2wlyhcwqe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2aywlbuxb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2egsnozdo.html


<!-- 参考信息 -->