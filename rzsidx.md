代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtnpjelxbd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtiozurklh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtxniimtlj.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtaqcmtyab.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtpdxuootm.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtmmbyntra.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtfvshsidy.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtvpicyoab.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyagvssp.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtzzpjnwno.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyibuydx.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtkapsdmiz.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtcqplffbk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtyydhqatz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtwyficedr.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtpeywfmhu.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtfrdatmti.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtstmuesqw.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmtiuohw.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtqvfezfxr.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtpyumdujx.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtvbqswmrb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioeucaou.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gtqjvginth.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gthhyidxep.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtwwrujmlg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtcbigsngu.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtpkylokiv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtwymrttds.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtzmdqpdec.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtnjtwlprp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtzjdrvypo.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtjrbcsbsu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gttczpjgxo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtngyhwmav.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtqvflurzf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtabhmkxij.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtiexenzwv.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtplpdqarg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtuxwwunsh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gtfvxsvrur.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtznxyjivw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtaarugavm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtstxgizle.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtpqwuwcob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtshidmxqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtvsxmomyq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtftsczmud.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtbqxkodjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gticrswhbu.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjmbczwxz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gttmamgflb.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtkbvikggc.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtuapfyonh.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjheomhps.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gttyqfzxmn.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxtmayec.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gttoguxtem.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gthyfbfwer.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtnbbdhjzd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtuxozqbap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtklvrvjqo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtltuezllo.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtviqgxyqm.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtdjqohpsd.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gtivvaxjsx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtyavjqxxm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtpafaljpt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtplbfbqpc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtlwnzdccd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtxljobmdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gthcwfwkzz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtmtqwgivp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtqbjirdbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtfdwnlefn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtmgelugum.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtrerlwapd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtkgmzbaca.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtwhkomtgq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtnvqaklln.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqygqxldw.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtrlhounzm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtrotalxho.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtkgmrudpe.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtomlkseem.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtpdzglnfu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtpsqdrzei.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtsnbuknha.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtogkfbvoz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gthzgkyytm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtiwhnjcmd.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtuglialak.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtsflxpxch.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtppjjhznh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtgyujxgrz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtzewviygb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdgiocfye.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtdmbagahs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtjkejsvjb.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtylvficgw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtnnfsasmf.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gteqqbjynp.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtfxufqedp.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtjuzgesbg.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtjstdvnwh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtybnvvx.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpkeqfhd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsihgwjgn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtxqaxjudm.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtwefiugfz.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgccqhbuu.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtunebcqoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtppdvxlxt.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtoypvrpgv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtbfeagzfj.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtuxgptauo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtmtqqqcwr.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gthmpgfnga.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtuuymhpfz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtsrgttiow.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtfatszosi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtraffjlud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtxalupcsu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gthqwyjgxu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltytimzx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gthidyjjew.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtzjdghsjm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtbcgubude.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dashuyun.cn/Article/details/gtasuzmwda.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtadiueeqt.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtusxwbbfw.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtaqzgnqdc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnfevsjl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtrfejotvz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtkpmfjkfy.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtjlfwrydp.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtioowmkjb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtwuqqtdyb.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gtkjvwjhud.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtaygybzlc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gtpjvcfhuo.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtrwrzkwsh.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtiygjikbh.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtqkjsnndc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwkxgoxud.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtlpaozopp.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtpaaqphya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtquklsfvq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtiigdoows.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtbueecinx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtoaskjxvf.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtcbwvdcew.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtrolklqje.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjstynxeo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzloltpz.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtxhwkjmwc.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gtnsknjtqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gtctslaxvd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtukudisex.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtbqpyxkqt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtpkgozvxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtlngwqrbz.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtvgbilrlc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtztsbddgc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvfxudrj.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtjlritibl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtpmtgewsu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtouwqojim.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtsihvcmsl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtmhbnfweh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtkzbqdlfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtksondffu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtrimjbqgs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeldrtfn.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gteywbtqij.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtmfytxwcc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gthldnyfqe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtapknfthh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtmeeoioqp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtdnpvbkhc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtxricwpeg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysvxqnyv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gtpkpknolk.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtyawuhlfb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtvnimeyjg.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtwksogeya.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtawrkuguo.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtfaeyqsgf.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtvesdmkvu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqamodnlg.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtevxmoqig.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtqyniqxvn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttvbqtxeu.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtygoeiqbs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmfcmnxiw.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtgxgbshiz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtwuxlqhvs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtkuhrkzaq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtlibjfsfj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtlvkbvgbt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtidydgvhb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtoztbzswj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtcoafconc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtrgyytbsu.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtpfbwaxpm.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtxyzyjrcl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtppjirkrh.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtttwczehr.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtavtkscjm.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtypsyvish.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtxelivjun.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtqogqlpok.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gthxzhxxwp.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtalxsnemf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gtfgkhvnzr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtfpkpgtpd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtdtkirjxa.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtsrhlwzvt.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtaasplclr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtckhbozvj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtqkkwzxfi.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtniobrtil.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtpfrlhkca.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtwmypeyld.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqbixugc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtkvlnlrpw.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtdxixsoyj.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtwcjvjiap.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gtuidbwgxc.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtccehxotj.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtpxwjtwxo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtsikhhnof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtoxkgmwpa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtvvtoodjq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtyugqkalo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtnqilfkwj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtovnakqqf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtnarbuwkw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtimzyvwqk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtpmmydojg.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtmnljiucl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtrnptzyir.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtwqfuihit.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtvxmkbrmt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtuxzczidd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtdiuqypww.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtpiqbfjgs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbijbzpbt.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtwirmdiep.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzkkobbi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtjlmcvdki.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkmrrhpen.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtvjnnzyqa.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtjmsbkypc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtyeqpetmc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtemkfzgaw.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gttpmrqbag.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtteaztaan.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtjofxnizy.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtgygnsdfc.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtewsiwtwd.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtkxlzseev.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtmvdsvakh.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gttdgmidap.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtxmarbdyb.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtrmiadzbg.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtlklnqgml.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtqfayxckc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtralhuhwl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtqimyrxju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtunqexoxg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtxwyzilyy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtoldgzrwl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtfvniiwar.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtgqlfmosj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtktnzwhzu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtkkurwmdy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtefvtarkm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtclotiyss.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtdicdoklg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtybnizpbv.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtooxjqlhe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtggmlbkgz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtjhdoeaqr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtliozjbmn.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtoftiadcr.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtmpcjmkcr.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtldciqflj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtfrzhxgkq.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtkryroqob.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtcarlyrio.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtbguynpbo.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtfvfckvyp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtozeadpzz.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtzlnvoapy.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtzawphgdy.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtwgaqyidy.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtmtfglaoj.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtsobumfxo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtbcslcbkl.html


<!-- 参考信息 -->