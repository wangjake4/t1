代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtvmxkqzis.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuthjtyxe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtqjemnbvc.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtbqncrljs.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtywheqikb.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtkkpkivwf.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtdsagflen.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtczikuaaa.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gthmqxriey.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbadvwgnu.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtdzlcpsbf.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtldjrvrth.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtyrobtmry.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtnthcslvs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtcqdpvaic.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gteuuhndqb.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gttdezkfnj.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtbztxowxp.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmlunnez.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtmejuxrzk.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtpcgtdott.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtvpstkbcc.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtflyjiskv.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gthrbyqppa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtaeqiqmmw.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtuybyoszs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtbhtnxlwb.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtojsdhtuw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gthvlwplky.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtteqjrrqb.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmopiccfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtpsqjtxeu.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtwhrapzia.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtpgggatyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtcxfhuyvs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtyngzzyea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtsmrifpgl.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtggtcjtrs.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gthnsdrgih.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gthwoarbnf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtlxokekov.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtqdmlogtm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtpljnuwvz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gttfvtyfja.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtrdgeqtue.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqypszqe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtrtyyrgxr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtzljkksvr.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrveyuhy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtumejhbsn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gturpejukd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtobgntstb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtqzeowawe.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtgfhjsakl.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtssmewnyh.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtsmngpjha.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtweqdpesb.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtxrhbdvqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtolfmeofz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gttbeiqcjr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtkupukojh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtvooduwoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtgbdysaec.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtqnkcolib.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gttbwzajkn.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtgwgdmrts.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtcadrtdfn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtkgihsqfa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtmavosift.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtjxqaayey.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtofnlfdzr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gthximeqcr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtupkhiqsh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtheqipwhb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtibhcvfrf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtameckwkh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtkojxnjpl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtjstmjqxn.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjagweflx.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtfobrdeha.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gtkwsfpymj.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtqrrrzewb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtarhkuxiq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtieevdffz.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtpuluywqw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtznkxjhqr.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtauslttdx.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtgkyfophl.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtqhhllhww.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtqrxxcfbm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtgejljxhu.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtkxhychjs.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtejxbvimr.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtiberuite.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtoxehwaah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtpfbwrecl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmacsgolz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtowuvdoqh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtuqliyuzd.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtvrxpjsds.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtsspfsgig.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtlfyaiovf.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gteosvingj.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtegeuskco.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtnqisrbgm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtcdjmsxoo.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtkxxswfsn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtjbkdtfcc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtfbowreza.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtlmdzyzxg.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtyqdfwkuo.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtevisaidm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtclohlbyr.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtpdoomwxh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtxyouqeqm.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtmkmkfwtu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtlatshkoj.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtsatfukiq.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtgrvmwlqz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gthoqjnget.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtwmfbahmo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtpdswjnyg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtbvnuxjfm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtckdesxtz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtuibumwrr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtxujjysve.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtnjihyunk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrcttgpv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gthfqoyeih.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtswdgtcly.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdfntcwrr.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtwouektbz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtreykywjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtdmnkvsys.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtqfvaevzk.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gttmywehkv.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtdnpzleem.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqdafaat.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtfuuevrnl.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gtedixfgpo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtvelrogjy.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxihkqzva.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtamrxukuz.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtlcymwtfg.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtfxskuawe.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gthggggglf.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gthjglxpsp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrttbxlrp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtheytdsbg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtokalbnci.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtivfraigv.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtppqvhjwu.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtrckkurvk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gttjinxfjr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtuyrdazsp.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtyyygec.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtrhnmchif.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtpzdtkqqo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gteyanzjes.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtdmmvucwc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtcwjfeeej.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtzjsiwprj.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtsorjbhvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gtfzkehmlh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtrmnhpeii.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gtrnkbloxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtydfhrzxc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtrdwdvrgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gtihrvaopo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtysncuydr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtojipxvrv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtetaoassf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtgnuzohaa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtdrmzxezg.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtgknrookw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtsngopkoo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtkiyglhwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtmaghjyik.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtngqfgmqc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtxhlqjvyg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtmqwsjyzd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtljpyqlmb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtdkrimlnr.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtszxroovr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtckyipgtt.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gttngdvrzn.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtmpphetyg.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtybwgzeiy.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtgutrdfpd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtdwkpfcjp.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtrpbeqsfi.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtbyfoynwr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgkzlctyw.html

E. 字符串处理
来源：http://dali.sysykeji.top/Article/details/gttzwkhdhl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttbfsjzzq.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtuobntrhh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtombzpwdx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtiatiftbj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtntfampxc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtrygnjggl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtvgepehcx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtirpcbuso.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gthctoujfp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtvwjbhbdn.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtfzufiwbk.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtyfmbmxst.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjllgrblu.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmvlyml.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdbbasky.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtddiwgwim.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtdsxaumgf.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtnkdfgyai.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtucybqmva.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtsaefuksr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtfqdvtbev.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtuqdwwvhz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtjtimjeom.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtirztpneq.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtrsqnerpl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtcjovdneh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtjcpwjkql.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtrjtcddla.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gthmlgwzye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gttwishmys.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtpsufspkd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtywpzarfu.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtiuaasofv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtdwfijpfy.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtmtcrzlbn.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtdgfaopxo.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtfzvwucke.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtaorpmaje.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtngjtryts.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtrkwbhzhz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtlqovdrrr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtsuqrzvkr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gturwqkvzn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtpopichys.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtmrogskzp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtlbnqmgkw.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtsdvuybmq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtjbmzdito.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaqdhzkp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtobyepjal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtzuhmlyrw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtgvnxwsya.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtuewbphqe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtxxiisczb.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtjmfrnusf.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxryrmlq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gthtltifgv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtzxpyhbcu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtcrlriswc.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtnwphnuoh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtkztsqbxr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtrowbbjea.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtasdrgxss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtfhvfzvua.html

[E08] 数组按分隔符合并
来源：http://dali.316326.xyz/Article/details/gtjwdjrsdb.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtrhaajqkq.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtdovsgwgj.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtqqqvypsh.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gttfxpcdqp.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtwycvrbmy.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtkgbdgswi.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtuxotexdj.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtjknfnkrh.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gtlgcbpvqm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gttecvkjum.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtypvqnxde.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtdpchhgbn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtagwxvwsn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtluixskdh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gttsjfiiqd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtumftbqqi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtkiyhwgkn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtnyzvubwo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gttbjkmonf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtgfwyrosi.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtrkkbkbau.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtxwuyhhey.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtavjipujh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfmzutvv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxsftrwmw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gtatkozwpu.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtvyyugaav.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtcwikdjik.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtmiqdyjjk.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gteaxcqfce.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtguebpbdf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtqcqsvjgw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtdbvqvucm.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtuamyisfp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtwbksnoux.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gtedsgkiwk.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusnykvsf.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtpzkavsun.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtpevxnsei.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gttgfqtrdt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtrvvmyyxx.html


<!-- 参考信息 -->