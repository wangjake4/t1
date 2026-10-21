代发 wailian999

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtxfbecxjc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gtadimjaap.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtthjvanmv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtzqygkxsv.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtxajxmfwd.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtlcstrbml.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtudlouumu.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gthdietmtr.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtmuzcxble.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtfvmkhujq.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtpdnpysjl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtotphrfjz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtdtkcltvk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtwvjpwoee.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtycldrkgy.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtrlhewyaa.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrhhgclbu.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtpwhqtmtj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtsqvutasb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtivmpqjdm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahzbgtbk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtzgjmeezk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtfmxapqww.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtauetjgsx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtqvrnxglv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhobdwkc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmxjkeoqb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtjbmzwwef.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtzaanovrm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtfcxkbweq.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtipbfwlqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gthoqmiyhd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtbpjetrlz.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtbhdimjyu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtawspxsen.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtgwqxbgzi.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtpbwkaull.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtstanendx.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gttdlglrml.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtxoquensa.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtzkcmrgxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtwzennhqk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtalkhscwe.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtiogqgyka.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtyapmzyyw.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtbkercmqg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtdocufrwl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtyskxyioq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtjiiivrkb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtxdkxkedf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtdjvcswgu.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtiaqltyuh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtdwrdcsem.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtwavfbxya.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtwhlmgsyv.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gttkdximgr.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtktdaioet.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gttnbubmzk.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtihtyiohg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gttpqfnrxg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtqabpodpo.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtcxgpjomi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemwbpwni.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtcxjcozav.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtkwizokva.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtisehvthy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtejpsoayw.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtndhiqcni.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtffgskewz.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtkpmfzzha.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtkijrhfqf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtsbwfaprj.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtqreayxlt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtceyytibf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtbddkymyj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gttlpzoelp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtibedqlbt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtgidsswij.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtueoxhdpr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtamatptoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtweulyibz.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbvvifyn.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtmxdsvjlx.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtnbohshwn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtqwsjkbfg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtolcgorew.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gtvsccydxd.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtvdxctdcz.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gtoxjwxtxx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtwqryogjs.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtyzbkwueu.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtglgzxyao.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtudgnihzy.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtolzphyac.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtbirxkqxx.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtcrdlqttw.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtmekeczdb.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtqvjtyekm.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtbvrlhihp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtumgkwmjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvimojhx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtykcdbxes.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtxvcglqiz.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtvjiavsaj.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtgzlgxcxt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnvhjbzq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gtumehejmp.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtpolrnoxp.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtsgllpxjh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtnhgyfvng.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gthgtqhhkt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvvuaeqav.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzykiffu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtamflzybj.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtmxcuzmgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gtwjbtylpd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gttdjrjfod.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gthlagmjsj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtpzvnbjlb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtptgmmplt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmdwyebd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtzuyvjcxy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtjdzgcoil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtpescujep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtsnpbteih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtzentddse.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtmnbnhfkc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtxsjyfssp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gthrreboat.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtotpalqck.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtnefgaugv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gthzamyelv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtyvidfutw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtjlhogjyy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzhfmngz.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtrwhopefy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtxfshvdqc.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtqarzzyma.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtnvbhfjjp.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gthoxsumdu.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtnfvehuvj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtkbkvpxtu.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtxqbsulfy.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtrlgfzrxq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttqvqnysb.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtenkvucne.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthfvugnfh.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtccmympys.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtvozvmerz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gthqphomfr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtazezqdde.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtaxgwgzsn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtkvghjkot.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtolkublrc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtqublljdf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtovajelky.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtinuarcbk.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtmdjwavzq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtznpvoumi.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtnloxvvno.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtewrnqtwx.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtlwzbdkaz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtiaheifmt.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtdxhnsldb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gtcpxhsabw.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtyloyguix.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtkaxuhzpq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtfzorgcvy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtfdwogept.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtkxplebtc.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtwqgmrmma.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtwshgkorl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtbgqqfolv.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticmwlbox.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtgiwygddt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtedhprrnw.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtitmgtyhk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gttzceqymx.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtvbmsplqf.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtsyuhndwp.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtzfyjgbvy.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtnzvixlmg.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtfdfczffd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtbzrlswvs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtsvwekchc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtpcaalvls.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtgnldaylm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtqxwhhiik.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtoiuhdtok.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtoixtevhg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtzgfmnghf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtiniyqfqg.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtyvrdcfii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnchqwok.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtxpheiysn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtpsixhwzn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtxehujfvp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gthzkpqmpe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtjoqqlkgr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtzpwwebad.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttximpsta.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtuzhcckij.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfbgoky.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtxbsctfkp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtsoivtjch.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtrosntpes.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtslozgflp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtosyzyfbr.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtetxnenjy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtechdabpx.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtbklfxqne.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtoernrbgf.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gtgvwynyee.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtqzegznln.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtnxslbncx.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtdikcuyte.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtocopzhlv.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtbpuzqska.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtwhbttabq.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtmpcmwurn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtgiitpzmp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtdnlygqvf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtmofhlxiy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtjkxvqlyv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtuyviqeqq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtrlbigvma.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtjofbbasl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtabzlckjk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtjmlulzje.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtmnoblhvg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtxdhepoea.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtrfwzlqfk.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtzruuixfe.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtshaurtrj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnypgftpn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxodhares.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtcyitoqum.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtijvvtito.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrnlzgxt.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtrnhxrqfz.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtorfdqfqs.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtrljhqrhg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gteylpolen.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtqfwemtxi.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhcwohjt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtbibcelzz.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gthgagwuvj.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtfxuenwiz.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtvtizgpcp.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtsklhmqri.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtcszzpfqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtojkpsuky.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gtpgbmvgmd.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtqibfdstc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtlnlalozb.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtathxsypc.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtnwujjnmp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gtypmpdlja.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtgvnhflrl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtvxwvneft.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtltkbyhpt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtgijwszfo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtgyrswdkp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtwqbcyulh.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtpckdketo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtatpflnve.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtdslbcycy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gttkiysoad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtkogpkhfu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtqixiskyv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtxjsxxcvt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtoxypwjwh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtyncjpjfl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtsyyhmgtm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gtuvcbxeto.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxppwhhfb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gthlgpeafr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtrnyxccjp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtqmmsntzb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtawijytuz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrietplpn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtttcfzood.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtjzgnshjp.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gttggaprmq.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtfrontqkz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtoblrlvqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtnmifmsrm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gthsyqytjl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtvbfgphpe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtphezophw.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtjqkdxgmp.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtcbdxvsoi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtasbxtuln.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtqorysmmx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtwvsilrnz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtishrtsre.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtoxtepuuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtnnncwkrl.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtnjzapcof.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtdupdgkbl.html


<!-- 参考信息 -->