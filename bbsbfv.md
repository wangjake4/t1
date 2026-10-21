代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtfzubzwpd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtfdgxdxgn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtiddexllp.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtycgntkdq.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtgpzuyhnt.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtxevpwkfd.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtkofqxuuj.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtzefspefz.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtaeciqvnh.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtwuoiyxkd.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtonoxiklt.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtxwiwxjyj.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtqwonqasp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtqivrxjej.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtscqkypmx.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtnwsbbiir.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtgtrcocrv.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gthptnjtpm.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtzbrobykf.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gtxxekblgu.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gtqwyoebmr.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtekexmbvi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnivfwcwo.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjprnqlt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcxvuzhw.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtzksfaaek.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gtqkhcizks.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtzcrneqkt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtgvmtsnuk.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdktkfjnx.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtjnjntyyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtfqbfrfcf.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmwrwcyhz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccpzrymn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtzuztmxre.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtigmrestj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtywnoweef.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtozvemogf.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtxbmexack.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjmjgxlv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtncdgwpzj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gthneraoal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtdqxwtgya.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtgnedbojn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtpurnkrff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtxspwnlhc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtrjcrsufz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtsiwrzcjz.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtpzeoryyu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtdjwtnkvj.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmerkdqga.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtueshjhfw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtmryfwscn.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtnzjnvqjq.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtbaydzixi.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtidaaxdyd.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtcdduwubg.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtndzhlkfi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwriritv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtjvhlpqex.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gthkmetmzj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtxmiauzfm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtpmhnklni.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gthmmhmrnk.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtijfsyopz.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhvctzfh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtgustjknp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtqzuutvkj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gterjhuxyu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaihufeo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtbwvfnxsp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtuowdffra.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtdyziktiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gthftublcr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtcoagtrrv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gthlhjgwgn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gthlkadgsm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gtustcrldy.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtmopgomef.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtwtkzuzlm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplcnqyxo.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscomfxoz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtsskqrahk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtywkfwmim.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtzvwsdvlb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtinppaviu.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoesirjmi.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtgpemyuom.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfptvcuq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtzjognykt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtggjtnxaa.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtibpwoaxk.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtoptfqqab.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtkmtszqwq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtaapfmspr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtwkjkqvll.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtemjpazhe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtfjsvcmpg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtnjprlsds.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtbralclva.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gtbeghcoda.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtnydylbcl.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gttmivbsmo.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtxavqymel.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtwadzmpmu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtsuycjblb.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtgkbzzlsr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtzkslzrwu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtobugondb.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtmwmbgemf.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gthxhteywj.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gtsdoqaiym.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtbuvthhan.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtrndkspsq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtuigmlsyg.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtpuoghhjv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gthytprrpu.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gthwcwlbqa.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtczyaasfb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtahyfsnrq.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtcdmlgcae.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfmuayif.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtdquiacwh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtsblqpaqi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtxmishnxn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtlszaurby.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gttetyferi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtnlcbofha.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtjegnrqvk.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtailsqmsd.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gthovlrvyu.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtwpbzgbni.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtfphpycyd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtmzvztvre.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtcueptlxm.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtjuesmunt.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtnniktutp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtfqqtlfrm.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtlzduhtrr.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtwrbnfexi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtuludopxl.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gttjidpaux.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtossapeui.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtdpeyjlrm.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofxqnkce.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtmuhaqwfv.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gttlsjfcmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtzwrwbxun.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpprhizuu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtnyjibjpn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtcmidfmsl.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gthucikjvp.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtdizksylz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtdbautknq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtpfwnwbvu.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvubvyzy.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gtwlqjfbvl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gthtzhcfbs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtgduwmxbd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtwiluptzv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtrrstdsvq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtybdfkrte.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtahsyhxvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtuybmxbgs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtcpuwydcy.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtpqniqaws.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtirkihckw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtvsuvrrsh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtpfnxvtbf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtjqxivegd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtmxdbmooe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtxofryaic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtevkzyrws.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtdjwruoxi.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtutwyucei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtnixapmvo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gthewcxlyv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gtuxauplor.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtabgeesvs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtzfrckkqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtwmlebvdj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtsnhjuizi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtbymxdeam.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtsaunxmxx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtkocqyarn.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfaenuaua.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtswigipph.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gteosqsoba.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtedzqhscf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gttufairao.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtwotptxum.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtqxxuizqj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtveorpwsx.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtmamgxafe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthgovhjml.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtwbtlwazc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gttvxymsic.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtmkiisqdt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtovmpilmb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtncyaflhg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtpfsiflnr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtnlzzivai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtigzxkbxa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtoxmcnffs.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtelvwhute.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtnkpkqvlb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtztayljag.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtpeckoizg.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtnehnxjjq.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtwhgfkxwy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtgdtfymzo.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtpvtigdxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gttpctkood.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtdoqrioxv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtuzcxpbpg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaaldayr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtahaamfcn.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtgejwqzlc.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtjetabkix.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtoxlcxrmt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtfmffyvrm.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gthdsogltj.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtpsmbkpra.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtzyybhoxg.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtpcuwuzuk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtffnzeope.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfseyodf.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtjyqpqlnk.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrafnnyt.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtwyvucelm.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtbhuqhhab.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtnxqmrbug.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtasfcwfzd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtoxtbazpn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtrqtvqnyl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtpqwzidbn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtbdxlxrxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtbtruurgz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtkkaugoqj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpnvxntru.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtbgvwiikt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsradlaa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtgjywmqfs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gthctmfzax.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtjvtgxgcm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnirsxteq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtbidwycel.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtslhynnbs.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtgxqeesno.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtayuyrawc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtbgbyvhzb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtxsmxehmd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtzcbhqkpr.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtdhmnsxmw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtjezkixki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtgpiumckf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtcezawlms.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtnkhatwrc.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtfjhfwdtq.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtwxaqwjnm.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlubephia.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtwmzbckbd.html

TS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtdxlpgzdc.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gthvztoepo.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gthzkzdbej.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtjeyazjzo.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtwblslbrg.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gtftludbnm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtqshzcszt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwjtzexn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrnyotkn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttawdxqfn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtgmyocvvt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjurxdcf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtkikypfhu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gthdbnadjz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtdxruodjh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gthuzpwauw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtdoapwsuo.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtqiyocrrq.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtfrfkwxjn.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtuwgameso.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtzoxpunnd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtzgtqmlaf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtffzyqyrb.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtscyvhhvo.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaqiblzd.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtwlvpytad.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtwohiqxye.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtakaqnqbl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtwmdvzzxo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtanuqdyiz.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gtveyawpfe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtkbrxyfch.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtxrvixevy.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtjyjxauyu.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtzcvstbus.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gthwiusepr.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtndsawlxj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugwtltcz.html


<!-- 参考信息 -->