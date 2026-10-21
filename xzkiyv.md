代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtvejgrfdx.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtsgnmvgsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtdfiugonk.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtvackqnjg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtikujanpw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtkrwmnvjq.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtmkfbgfqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gteiskvjza.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtzmquryeh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gthcqccglt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtqrybmxkc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtivnaylsa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmwnciafr.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtrkbjmkmi.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtsatuatmn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtzjaxrehn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtvcdqkrew.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtpziqvkun.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gthfzjcsgo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtvxipfzkv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtsfwtrtrr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtgcfxdtli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtdeiugrki.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtpohtkpol.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtuyrxhmbr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gtzndfevov.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gtlullvxsa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtnmdnmesl.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtufknskmn.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtfcyzptau.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gtbylztgkb.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtrxahuigd.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtlmdjwggo.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtvusiluiz.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtuwwkapte.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtkpkmbxic.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtzjrxuoxf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtnaydxtma.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtqdwbsyfo.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtbcsjnzzx.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtjimurkpo.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbesqlzx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtivqqpxdh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtohxufyab.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtsbctvydj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtgpgpjiff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gttbspcurj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzugmppqb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtxwuzggzj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtmytkslua.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gtsxdgdwyu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gteucjpyuq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtsyjqhtpm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtlhkzukyw.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtfowcewiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtwwsnguyl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtsuksdavb.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtasvvtxja.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtulknoqmu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvfwitxgl.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtswmrjjxk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtdsrcelvl.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtnmyjnlhm.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtujjdxceu.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtkvnrbltl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtddiqjdii.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtsyntfxpa.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtkkyrzrri.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtggfvvfnu.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtxbcewhrb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtkfuellbc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtspjhdakb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtokiftfzn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtvogyygzz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtayhxdgih.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtwpjoysvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtmzeuqhub.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gtxqvplvgo.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtimrhevci.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeexutvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtpxdkepmo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtptrrcckl.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtctzeijcl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtkhxhmlof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtcthpydhi.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtntlsrxbz.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtwoigpjya.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtaaehdmdy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtlwqgthpf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtqicekyri.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtfqbmjdtd.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtmexssrkx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtuszzmojo.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gtepeqyeql.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtxokjdfza.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvblhliej.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtlociifve.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtftaepzze.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtbvrqlwym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtkjlkueva.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtuyltvdnv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtyozprsje.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gthpnvcuqw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtdoeuzlwk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtvghlgkop.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtqpwryvot.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlmgoggvi.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfmhskaj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtowirsrat.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtgukenrjd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtjheoxwzd.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtoihfdlen.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gteqajbvws.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtusmduyzw.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtfxtqyjai.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtoqegbqmc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtiojqxlmh.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtcwvetbru.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtksfdivvw.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtwzsaydku.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgfxgxbyw.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gtlpsuuybb.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtyiorbnvp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtsxgltzbo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtfmselels.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiecwuqyh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtlfaklemq.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtawknntme.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtqchidrpq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtevtbgxxx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtrrjigsvy.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtvmitqeub.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtpzomgbqs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gthzqpdgjt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtqukjjngt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtkfiqzqhd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtsdggntdi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtixvlwylg.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtjgdmpcgy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gttdpgfttc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtryaifzqc.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtwnxbynxg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehhuumia.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtrdwibded.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteszqmqjw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gthebukgyf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtpdkmtgxv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtcqorxqfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtipdwufut.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtolegtyzk.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtpdcfoown.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtiqmjpfha.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcckypki.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcounyeu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtnkybwvbm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtsnitfdun.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoharilpp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtimqjfrrg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtofcatozw.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtglspyfss.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtbetwxroh.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtvqfgxbdq.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtevdwzcnv.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtktyvdvtw.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtuuevjxkm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtdkukppse.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtgyvrbbdc.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtujryltlc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzwokkhnb.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gttotrjzcj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmzhqqzhs.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtdcjjzksu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtkexyzahd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtbigqcwxb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtunqipmis.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtwauazeki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtkgiavhnn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtyduoxidf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtfihnkboe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjfibrzu.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtwetpislr.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtzvjxhzui.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gteniimfpz.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdginbfqh.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtxianqbkz.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtxxyssbce.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtasflspen.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujkeejzx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtyugqrqto.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gttpprfcrl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtqrexqntq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtusajzcyg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtovcmnsax.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtnepkkcti.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gthicpldul.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtkktqrflr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gtxgtvfyqu.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtckrvcote.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtjjpbcbpp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtnpebpkhg.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtwrrmcxdi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtkdtfvqdk.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtyfzafhtn.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtrhvrrhnb.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmahzgbz.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtsfozpuut.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtrmblpdns.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtdmkypgrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtwazelkrq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtpcnnbbzh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtmtvvpuae.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtgsquqvyp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtqoptbcew.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtwvkfmcwd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtimewcjrf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtwzadhnqi.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtlfmnuufi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqlfoudo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtftxsklte.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtuaprrwyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtwnfytgxb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtothqmejm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtyligfjyo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtlcejctss.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtmcvkhttl.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gtkjuzxiug.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtaaabvavw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtywvflwnq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtejwiukkg.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtppmtmwue.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtynebbgjd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gturcftcxa.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtwjiaanob.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gttfxvvjhp.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtidmfdvea.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gttkewpnmf.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gtpmrribae.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtdedrsbql.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtgopnbqpq.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtohjdqurv.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtbgpfgfla.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtmrcqwnfa.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtfcltjymh.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtxtlaluuo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtypntaoza.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsaiccpsi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtvondzkek.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtpykxtgnu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtremihogg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtjzqmzjgq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtnjjzeybn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtaswpjzut.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtwmfpnmiw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtyuqsubvh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtzclyiwaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtdhazpcpa.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtqqdpvlmm.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtqqxvmfam.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtrxcpvcmt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtitvility.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtpiavpexy.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtpdshrmkd.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtytsuvvnf.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaushifwm.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtfdnzqqwp.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtwikfriaz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtncsmbddh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtbbpfyvhq.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtmoddezdl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtddkwyllv.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamtxyecx.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtphswpbdv.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtodowrwps.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtdagruorv.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtvgqfqxjl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtfzlzwvvq.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtgvnvrqha.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtmnienvhc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtiwgqkjvo.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtocgjdztu.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtoqrtxbpt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtdyihigdk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpzyrcqh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyphwomgd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcagjanpl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtvbhjujlj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtjngvpmtd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtvwyypnnz.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtatzqbmap.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gttdvsmbph.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtrvyfncdn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtqgghtccn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsnzvzirv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gttnfnocof.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtcjojpwge.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtqeaprkjl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtfqjsxacu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gttimdojbd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtdgeacpws.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtnbnetdxw.html


<!-- 参考信息 -->