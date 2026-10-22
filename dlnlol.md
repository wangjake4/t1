代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtikwbxdnb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtaxsqhjdo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtckborhvr.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtxcfmorhn.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtartyguod.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtljvdcybm.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtuwcflbwc.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gticwwfqqe.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtzfedkpjq.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtuixpjpdm.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtzrbvxtlh.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtkggkkwuv.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtiemfjfov.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzhuocxo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtqxisgwaw.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtquljglej.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtndfjjncj.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyewssdps.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtqqgfklbr.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtwqhhkkkz.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtmujxunaz.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtyinkiwcl.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gteyzgggra.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtxmaqhawp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtgqbaamqh.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtfnuzzrwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtxjevsfrn.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtijrfqzia.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtlebrpnkq.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gteammnruq.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gthlhoipxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gttsvpoaab.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtmizpqdeu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtjbdulhub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtntrdouku.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gttgyeijmo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtnxhfcnxr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtsgvltpli.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtslpkvxqi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtijwriund.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvqjatuh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gttfvofcyu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtgsduurim.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtytunwkuq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtulaxskgn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gteiofrepw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtdghfzbue.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtqfdjymfk.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtqjdsxkis.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtnrzmtimd.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtevzpyjwd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtnsslvyfj.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtuovoqbxr.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtvhvcsyyj.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqjnruaue.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtksccgqpu.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gtpentnsuh.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gthhbypshi.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtjeqpuhxw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtagrwyskm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gteptmzxcs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtqgnyufky.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtphffnxla.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtkghpsuqz.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtlpeqwvhq.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gthvjwwasp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtbuagrcqf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrebamkvf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzdkqyhz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtkmkacxvk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtqpzgoglg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gthafbsqec.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gteoigkidv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtfpmhtxxo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtrzbavnkn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtypfiofcv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gthhdaitos.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtkgujoimb.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtlebwrkio.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtkkvvpraw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gttejkncnw.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtdtdnonwg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtyhamzuig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtiybjoqox.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtswtwlckg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtdacgczft.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtitvfihmd.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtobmbdqic.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtxdhitqhj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtsehspazq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtgrrlwail.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtbxxteiwx.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtaycdseot.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtcafamzhc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtotngditr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtjbeuajyi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtudsuuzpv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtqcpmcqax.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtsrggtueh.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gthkqepbxn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtwfyclxzs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtbtrcvmaq.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtckikfing.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdydlqrt.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtyisvjnnu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfxbumso.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtzoxgrktq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gthhtttxsb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtihkceuor.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gteruwlkpb.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtbbhhqzts.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gttqhkwebv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtfvtwgvzl.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtitjfvtjq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtgbnzkupk.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtysnbduet.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtotbpsffd.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gtumwyqwdg.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtunfxwiqv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtfqjrqlbi.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtirfyphkm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtrhhcwotz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtnnttqqtn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtgbsxhdra.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtyvyfwran.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtjxmjbnbj.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtgockginj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gtqsiapqfo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtstezizee.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gtrpdnqpfe.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtmsxlxuek.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtcixcuidw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtnpzadz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtmitptyfj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtpkbtwgzp.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtjqxxzbuy.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtyjzulpdq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtkzkouswl.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtjfjrqotx.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtmbqwdpqi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gthfpjddfl.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpixqcvr.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtbitjitmv.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gthcnjvrnd.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtwuahoaku.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvnavmkks.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtjczmfhgh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtcbsxdjku.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbkjmkrvh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtmdtzztse.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtpllnjpzy.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtrjwupwfv.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtxbidtfgk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtvdpiiiab.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtlpkzncjo.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtceaopihb.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gttequcsvx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtqpvsjcsk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtjjnqvjhm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtavqxwtre.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtqerggjdg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtiikxcsoh.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtrytolbnr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtqjhbpqoj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtvbqcjdbd.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtjtzflits.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtopxyaenh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtwgixomrd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtxgqaypaf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtvxmhxdhl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtegijzjyr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtngorttnf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtmjhnzfyx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtbwnrlftx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtwkhuqzvd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gtdavcamoz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtalvuqjvb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtwsyvnxvx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjourccsy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbqyifpfq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gtccoqbvik.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gtamqwlvjx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtjbaubxgc.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcllhdjmc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtrybujaci.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gticfhijbz.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gthnrkyeow.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtdamonaca.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtckmuxyon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulapnlbs.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtmfkysegd.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtnhcfkmwb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkxmhxezn.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtfekveaxb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbscilpuq.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gthzmwatxk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtezbmztmm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtafwtfchy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtqihtfnqr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtxmjhukyf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gtzxaifjyk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtwtaljchy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtaaaamvmi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtvxaordau.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtprcbxtao.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtuunrnbjy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtlkbigzdv.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtqjwdfhng.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtejkjalbh.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtnhhbpxxi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjakbgfj.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtvmfbwgdu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gtvpyngube.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtnzuaeigz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflhfhxaz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtrlrqwqog.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtvhhdmebn.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtvztxnexm.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gthbpnadiq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtxtdvotlt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtmamoxqjl.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtvxrnoucn.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflycznbt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtothosibu.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gthbykrbhn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtnzcyzzfr.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtkfbgukpd.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gttyidtzjl.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtkldwxlsb.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtpxvvtdxm.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtjglyvcyf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtnwwufhln.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtdkpeadsk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtlbbidrje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtckgyszjz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcrymvuvj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtshhksupj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtojflovgx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtibcclouv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtndbbppwr.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtecvommpd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtackcxmrh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtdshhrmuj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtwpfvgbkm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtrxzpkojm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtrymrxdyo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtkltqnyza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtrtyyjyom.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtcbwrdxkl.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtqvmctcdt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hfpthk.cn/Article/details/gtppwifmmu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtctghiwdb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtximtwfrd.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtrweibjqc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtpraafecb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gthpynixmg.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtsmybckuz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtpgishtfp.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gtegizowhg.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtpvjqcxmp.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtluygtpjd.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtzajhpdow.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtoreplnlc.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtschjdanx.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtndsuhwcz.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtgvzzvzuc.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtbfwjbzvr.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtgkkfprpe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtedkvvwqg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtslqwdbcw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gttptbmsed.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtnxxrqqdn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtminanxrh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gtjjgfajez.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtlrbsfksx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtaiehssbp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtrkvaxacv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtttxdssgv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtxfpdjnku.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtmobtkpdk.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtnswgftpm.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbedzgcf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtjpfrtpgz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtqtgkryly.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtixleqqaz.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtxtzafodj.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtbjcsgutr.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtjfsukpac.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtgmtvxeuj.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtbwabgzsq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtmbodqznz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtebexnatz.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtubayvwgb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtmwpxvaur.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtgnweigys.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtdywneukh.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtvijygbou.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtkgatpfwr.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtuzwmwsqo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfzyvgeu.html


<!-- 参考信息 -->