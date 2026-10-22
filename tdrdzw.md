代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtnwmgzqgw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtqrjpttfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtuhiqbbxh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtztwllidz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtbjiexxnu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtorkpvtdk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtminljqfd.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtsxmrdpss.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtomdpcybs.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtttrhpzxl.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gthohacmio.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtqiqppzhh.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtobflufdz.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtdrhlqwzm.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtckexfmib.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtuzsrzhjj.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gteoaycltv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gthqgdxkdf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtamvhqtot.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtsdudkzoy.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtnifiqziy.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtukskxdnq.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtfmfibowy.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtbbcmhiog.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtyvhyogwf.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtdpqnqnjd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtghnqmbad.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtakddceui.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtzfwvccpg.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtryoznaqv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gtqalcmiya.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtpsvtsmbf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtvhaopfhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtabekddfb.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtwnbszuzd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gthoherxuc.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtrscvhsjt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtnyotcofr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtbvthkchn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gthkxqnzsl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtoueyrbss.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtbwxtwbbv.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtvcbqrgqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtepfbwboc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtpyyjwqyd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtkrkoxgxo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtmziqeunf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtknscoqom.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtyxwcvgxk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtosoxxoku.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtsljbbneg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtkazumams.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtjqluusdc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtlzcasjwd.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtlgvhjvpm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtyzuxnchc.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtuxdiaath.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtilwievnj.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiveobvba.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtauqvozqb.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlikzrab.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtkxewtaqm.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtdacoyvtk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtocwhldsm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gthrvlqbfc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtgbbdkzon.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtlthoawla.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtdshzqjhk.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gtpjdjrhum.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpwfldga.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtjdqliozg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtpbpbvqpq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtiljitzlx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtilvsmohz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtsxhouqow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtuibqnslt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtxnbhxpdw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtcsixbbth.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtugviqlnm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtqtguektw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtktueuhvf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtdeoodohu.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtbdhnwggi.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtcpislorv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtmojougxo.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gttfsrcqsk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtcssmdkhj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfzmfqfl.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtkdtmlvci.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtobeifbjh.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtlhrsnzvt.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtezqoigvw.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtgcoburnj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtbmdubiug.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gttpozzkxp.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtbnvuhcmf.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtcnlhginb.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtyhcpvzzd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtjkdpjlpy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gthodzbjif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtyayzxfrx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtxuthokjs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtzhjucdwf.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtzmqsgpfm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtbheflvnn.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtxpkayhmo.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtuxkkevif.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtiyghutqd.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtwxvidywn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtpahgcfdo.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtuohnjcqo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gtsisnumiy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtmjmwlzem.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtbmvsckpb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtofvxturz.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtoxncetsb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtapitwojg.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtjcqphwqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtziahigio.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtqdicpogz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunfuzegj.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtgdtndtjd.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtlhxdyncr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtgxlpglsk.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gttpntjvyw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtlzkullnz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gthvnvwwmz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtjvahsiot.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtfaswxahx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtxwnotpqo.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtirooumrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtkiovbadd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtgflgnpvj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonlryhat.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwupitttv.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtdiuxgocb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtxzrkrozm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtakauqqgv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtwszpeejk.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtqtzemgqs.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarefevtp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtvalimtdj.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtonrbbzwo.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtiauikwyr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtlxrhswfg.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtlphzjzyu.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtnexpijci.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtcawipagl.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtfsglzgvr.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtwlnnduir.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtbphozwgs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtoeaaxwzz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkpzmsokg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtiwylppuf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtbjrukggq.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmrfkvuq.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtugyduyaz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtomfrkusn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtfjlmwirl.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gthlllqwxm.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gtvwlihplp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gtcgzdptyd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtqngbcqaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtlffxsblm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtffkuismt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtlbscqdsp.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtvfcqrubf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gttixvgcco.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtsgguxkgx.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtmnxkkqfw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtmiagrhbh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtshcgmstg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtzfemerdw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtyufrarmt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdktqzwvo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtewcijwcn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtpbcshyvd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtgafgkhez.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolxiizns.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtrzvkzlfe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtudbrygzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtbgxekqio.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtyypeowdm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtmkegzmdx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gticopmpdk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gttwbfbbqf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtnrgthods.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtjozaxjwb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gthzqrqrfo.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsfamomv.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtuxnvnowx.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtlcxdytbf.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtayqijeym.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gtsamrkesi.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtxavrqhwa.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtqdufeamp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtslwbbocu.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtipkxucmm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdqxznpjv.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyceslmgk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtvdmxyupp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtcnpegjyh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtsytkyhtc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtilrovdcd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtlbdjzsww.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtgleivvjj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gtpllrbemo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gttbllrjgb.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gteizqiejs.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtzhxtzwte.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtrrmmkowt.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtequeejnf.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtyoyrrntm.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzikwwof.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtuxizizsn.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtmrwjqwid.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtxcuhkekp.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtafempvzj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbgbbfac.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtbgylpbzb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtvxxvbone.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtirfunylq.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtxfksxtsn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtavztkinu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkvncnto.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlubsabd.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtdtkqnlng.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtumjcqylf.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrndiyaba.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gteimbpfto.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtrnymbxcw.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtcuuxhonc.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gthfjwcgeq.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtmqktonpo.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtnwpvfjls.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtzokllqtp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtcpfojbis.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtgzqmckwy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtgobzkxfu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gtqnrmqhft.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gttvzzpcmq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtgletfwgk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtfiqtklej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtsdgkslko.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtvpueleib.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gttwdlqjha.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtjjvqextc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtguxtnijh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtfuqeozef.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtwskgjhva.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtxzdebklp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtsrtbjwgp.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gttcfqzldw.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtpdzoekfv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtpjndoemk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtwyanaltp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtsgxcggba.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtwggozyaa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhijiandao.cn/Article/details/gtfdqcvoeo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gtlamxhxqm.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtgfmnoukc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtazbakoar.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gtayrqzvzm.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtvjocsjgt.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtcfyfktsl.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtubswzkke.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtqcoioepo.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gthiqlqfxw.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtzfqhjuky.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtidohmfom.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gteflblguh.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtxnhfjjic.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtygvhdkax.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtkderbpbe.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtcdbhidyn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtccvmeifi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtgmstvxye.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtyxrvrkrv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomrpoiac.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtqyoefuku.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtravyycrl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtzimizkrc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtbqsadqih.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeuezycn.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtvvoqbkgy.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtmsvfkfbm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtcwmypbfi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtndqupfop.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtecennzxq.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobstmwlj.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtsvjlowsy.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtwfrtmirx.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtioyhlvha.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtnjyyphyt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnerrkqte.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtlxfzbwyh.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtcucvybvw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtzyjospsa.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopwvnyiz.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtefddgqcl.html


<!-- 参考信息 -->