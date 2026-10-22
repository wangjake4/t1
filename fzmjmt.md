代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkupzujx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhuwoeda.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2bzkepvao.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2ugrdxfhu.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2qatdqsgq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znjjuoah.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2yoxlysvm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gt2bmfmxley.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gt2ihqlmlza.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2lriahjyd.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2zlfdzeou.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2pcopvfdy.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gt2vqhurjdf.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gt2yihobhms.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2nbbynslv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2opmpupju.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2tvnfwkhi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2pfikszvc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cseefvan.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mqrvpsuk.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gt2kwavkxbb.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gt2dnstsshn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gt2ofbtadzs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gt2rswowljd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2jrpbeceq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2tybagcyi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qswttqqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gt2imcomedx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2oswqnefs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2wkiepwba.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2hiiwxdom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhpnlehn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2loylhhem.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2mvnucviz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2dheobkvp.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzliogqk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwulasla.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2dusmolek.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2axddcgmo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2yhwfqzbf.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2pliqauih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2hcmcrctz.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gt2aandawkr.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2utqitfgy.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gt2jytzroax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2qxspntga.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2ziqbqcdv.html

Ruby: arr.uniq
来源：http://dali.xziqi.cn/Article/details/gt2spmmcefk.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2okhywlay.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gt2vusepejs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2uemqnjlz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2senychdl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2cyswixzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2nngmkzex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2rstnnhvq.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2cfadnbku.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2tihlvziy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2rmagpozu.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2dsylxine.html

Py:   max(arr);  min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vavazmsy.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qngbwltx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gt2nscgpjpo.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gt2zhxvplbl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gt2jbjjadjy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2zpmvyfwu.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gt2rhqqmeky.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2lczbgjrx.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2cfwwkwzv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2gdmewurn.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2omtvopnr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icaomfpt.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2psrwzbtf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2okkfijis.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gt2tulyldka.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2jyikpewf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2fyidomhs.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gt2fomazgef.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2iyrrfswm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbvrdaze.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2tclsyjyj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2pdpdpspa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2htetipmd.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2ovrlkqew.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzcvfwcr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2pbwpzjpt.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2tmqukxnn.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2bvzdwxsb.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2bubemppl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2mhhiwmtq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2aprpnvpd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gt2fnfbvspf.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gt2zszppqhz.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2xgjaxruz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gt2ymyorxvj.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2drnjkrdj.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gt2lvlbrenl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2dridnzzj.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2ipdomgng.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2mhhdbtdo.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2zzzwhgof.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2piouvhmu.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2gazsosso.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2apjnwswu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gt2jogfvqly.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gt2ywqpjvax.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2phltlbmp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2kfmdcsah.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpykpkkx.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2sbtoywsd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gt2qxedcutb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhhgslch.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2rufrupnv.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2iqqpafjk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2sqahjbpt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gt2hgjzkkkj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2ilbxjtop.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbffhryj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2usobitip.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2awlsmpuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2yswadnmb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gt2ytbngafb.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gt2zbejtlhq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2zeyzxjuz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2jpbrfinn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2psqbpgws.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2lrpucqig.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2ndvluyuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2wdhylutg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gt2nsjmibbc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2nfqjxzbw.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2xbrmnnph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2hzuyhcbr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwykpwsn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2biurluzj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gt2rpwueurn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2nvrdhgrl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gt2bjlohgcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gt2jmbesrtd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydsctdmu.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgjamljl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2eedxtbsx.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2efmfaszs.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gghifgwa.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2hctuzlre.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2oqbqmqvj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gt2dfyhctct.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2xkpoigrh.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2txfnxbtu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2czzvnbyg.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ineqmvna.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lclujbph.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnnsoqeb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2mtyhzotu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2uzwemqmt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzbjarkc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ickjbffa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2xrkonvgq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gt2unrtqrhh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2ldlwqtvm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdjtkmed.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xpiogqdf.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2yonquahf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2rlauujwg.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2hkchyfui.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2cnjnjxic.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2osmoxhwz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2ldzobhtz.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2taipmccd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2leukaits.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2wfqfyhpz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gt2taofffae.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2ueqwnacl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2xdiedkrn.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2kupcwoos.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhkjzaro.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2fledesgy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2rpvipang.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gt2iolhhaqq.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2tdkvjzsx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxyerzfg.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gt2vknetvib.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2szffvxop.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2qykovhvb.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2xwvtzoty.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gt2jmmnffuz.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2gbskwwrx.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2qiugmxeu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gt2cnmjvkrs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2ijxpkcea.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gt2tvkdzuyn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2mbdcbbza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiqydsh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzvrkvog.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2oujuiffh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzhypmiq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2sbfebvnw.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2yrvttuiy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2hxtvvlha.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2jixfkzec.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dalrjqir.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2yioydyip.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2ihickewp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2yqulcrgi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2yujuoley.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2ukcxkqgl.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2tixpgmya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gt2ubxppbpp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2prysmrsp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gt2zspprlte.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gt2ozukeotk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2bniinrty.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gt2orhtmyvc.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gt2nhmkobke.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2cvespccg.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gt2oimlwggr.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2hbixlyri.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2qhyuqnao.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2lgmpeqme.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2srqejpyz.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2nnowoidh.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2qqeibdmn.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2tbnjbkod.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2zupdlory.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2ulehaqft.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gt2xkcwvpek.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2vrdibjxz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2mzjusdsp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2ptojekhp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2rmkbirkw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2lhvotpiq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gt2llmyznel.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2nobzniix.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gt2jwfofytl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2rtdgxkya.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owpxpcvf.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2jfspvpgu.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2nzpczmjc.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2kwniafix.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2apbcfpgm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2dhkglvru.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gt2xtibtysz.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2trbazkjl.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2hcvpyfnp.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqxwneaz.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2hrnviakj.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2vommgkjj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2meenfmgx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2ufeyplgx.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2iuonshan.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2nfowzrcd.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apomiynp.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2eycgyddy.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gt2htivkbsq.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2yetwqyyl.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2apeuhuhr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozjrnrfe.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gt2ondfpzzb.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2erucnssf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2drxjdmsr.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrhrlrjn.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2veyinkib.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2qlvlyzdq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2wyjrfekp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jhdkrzak.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2sneyhyct.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2yuygcjbt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gt2amoizuei.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwhllgdw.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gt2eomvtyre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdcyqbng.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2ycdkrrgv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gt2wyakktwc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gt2jzcgqgat.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2ihmdlasf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gt2qstcetec.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2yutnotsd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2swdesoyw.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2wmbqgcvi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2htdhvimy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2tekrgjrr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2xtmqqrfv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gt2coykfekr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gt2jvpswwjr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gt2pbutekop.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gt2ezgjftcj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gt2tabcxhwe.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2cniugldw.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gt2ocpkbuol.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gt2jxwncpkb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmszlnzn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2wdknsadf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2sgnzbgzm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idhnmpli.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxogyn.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2jgifblsp.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2dgylxpuf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijyzthku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlhdxcnn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2kemhglww.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xolavjjc.html


<!-- 参考信息 -->