代发 wailian999

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2vcpgtakt.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gt2zxmuexpa.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2ndruqmlt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahquiuzp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2knhcebuc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2saveprqv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2suapuheq.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2yszeaclk.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfcvctnb.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gt2twlvqnub.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbdsbwav.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gt2tpsuikfd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gt2oubqnqak.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2nidhomlz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2nljlgdyp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhutpht.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2qqsbbfjw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2ajtxjzfr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2hiytkfkn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2puvucwnc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gt2pjpezcnd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2cgnearsh.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2jjapajqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2cvyndjtp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2mvxsysvp.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2dtzykssq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvjwkrxe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gt2hfkfocim.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2zyaxarob.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gt2tpizjurg.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gt2soofdszp.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2edezfxqr.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2toezhjoz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2wquvtqwm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gt2gibtioqe.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2bjfcjynw.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2eqlgkqxb.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gt2fdjolgkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2lsqqvieg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2nlhaxtgz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxlychgq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2lxgcgmny.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwklnqle.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2nxpydmyf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2kndujswi.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gt2hnexofsf.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2jadblxqc.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gt2xveyeury.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gt2kuhdeezl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2kabrddnv.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2zucxmppj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2dvkurmtb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2hapbiomu.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gt2cwabwfdl.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gt2xacgfcau.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gt2upuzbulz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2izmpxobl.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2esdjrsxk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gt2yvvhcpbk.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2gncgspad.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2rohcahlf.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyjsprns.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gt2sikloufm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2oczylkve.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfxugdcr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgkynrij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2jqocixru.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2lklrjujb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2remxrkvi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gt2ltmfyyir.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gt2cfcvwfhk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2cbhjdiyl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gt2awnebwur.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gt2asylspql.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2vnwbqgzq.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2brskzqdf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2bekskksz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2voafbrdw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2ltlrcjoq.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylvcucys.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2ugllihvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gt2kuvpwbre.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gt2azynihta.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2ppeiosnt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2uiqsttfx.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2cudadsgt.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2cbmsdwbj.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmhnknbs.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2lqddccod.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2xhdzppkt.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2dtamhasg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwjiakm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2iehlvgqd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2mamplpjr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2zqfbzqaz.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gt2hhfoykww.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2bpasixkv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2kmpvucke.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2zbauogby.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2msywtqlm.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2vpvzizcr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2fwkymiak.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2jxmpfcso.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2dyzghsdb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2qsdvicbf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2wjsjqjfp.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2bsofeobo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2vxviqxom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktuuibda.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2ymhcqorf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gt2mvoyawho.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2lvunacey.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2lddqycmo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2wjpurzju.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2hnprohal.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gt2mscfovbp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gt2imrscppr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2yayuaxdt.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2uricgufj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2uwdfnvpt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gt2rprzxlwq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gt2wqtahfqy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gt2twzstkpy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2trowyjrh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoqbwplz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gt2sbqtslhr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2oufxzkso.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2rvtdljoy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2humurqja.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2spfnqkwe.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2cqjgqlej.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2eauslfaw.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2iuvgugtg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hodcumjz.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2vvxyquvw.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2izprafhb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zstjyzkd.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2kygvkukt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tisovpsz.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2xktwqksf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2npufhcqs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2haiutapo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gt2onjcruha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gt2aogyqvdj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2tymvbich.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gt2zzrgqhdg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2hpkgpvli.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2xcytzlok.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdyjdgye.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2uvkafpuc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gt2hubhafzm.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2qkwrowlp.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2wmqzpqqs.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2hjzumgmm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2orfbyxlk.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2lvbnhqkg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gt2pspjdise.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gt2hlhpgybp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhbbrabo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2uelwswax.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2faipgupt.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2lvrsywzp.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2xxjvfnhs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkbmdmdy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gt2hlyglvkm.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2rizbtscs.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gt2mnqucjud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xapeafnz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2opcjaacw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gt2rqtmxymv.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2pejmqupg.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2omeghsli.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gt2fopewbun.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2mwvfplme.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2srmblgea.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2yeffyoce.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gt2ensshtdo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2gvotmpdy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2wowjhozl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2nqwgdoyf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbqnzaka.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2avoeowim.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2objqmvfu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2iwqsdoga.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gt2wonowqwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2rcrwgzeg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2qgancvme.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2vmrltktv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uduieskj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2fluhppxv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2isnrztos.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2phnuszmc.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2uigueavr.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shypsfvo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2kbvgejir.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2ykhvskub.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gt2anczuvuz.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gt2gcyrhzbr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gt2rfnknctl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipdbuost.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2atwgflhb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkhbumxe.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2mthpjnbv.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2siqeflde.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2rejgmwjw.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jygjviqy.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2rmluebxz.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpbwnhtx.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gt2vqmqjrtz.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2jchjglxz.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2zmabpklg.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2mykunlrx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2hmmgnxlv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2lrmvxyyj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2quuohtvx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gt2vlvjzwsd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2aepclull.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeermvrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohbzglpi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2nsnylftv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2hjrmjygg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2qdmuekns.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2qhdvtjzd.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2ryhzpnss.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2hjqynukp.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2ophkgptz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2dypjadvg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2mfvegwqq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2grjfzzln.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2cawmtfas.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2gzipftoa.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2warmdlkw.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2psfaojsy.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkgcpzgu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2deinrmtw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2mhrfzoyb.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2zcqcvhmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2uxanlkvh.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2sicbvesb.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2nlyomyze.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gt2irnrbcay.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2cezffzoo.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gt2whkovuqj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gt2lmurrcxo.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gt2hcztynwn.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2aylnnihr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2okyylpus.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2filfdzei.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gt2minkbglq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dacfblia.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qxixumui.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2crnyfyrf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhhafhov.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqtwcrhx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iecmbair.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2hkbcnvbz.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gt2xutdnasq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gt2tztgljjf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gt2apijgboe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gt2nxtefntg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlcyquqa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gt2zkeifkas.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2phbfzgsc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2esfkahgo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2ujodqzbb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gt2fhwtxbab.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dsjkmbwl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqykekpz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2kcpmqpri.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2wdfpdimn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gt2yxgslfic.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2zngfqrlk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2altednqs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2ueuobgnm.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gt2vsrrdqbk.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gt2eqkmktwf.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2ljxreuhz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2fwbqjjnn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2jnsjqlvo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gt2bmgaegcb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gt2wsigdlpo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xliwdyem.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gt2faimxlum.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2vhndusod.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2sercxrgl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2wvavfqmk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evkafyjr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2zyafowan.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2lwckbgbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2wppwbgcc.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzenusee.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2aljpikqw.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gt2watofzjv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbfmkgpo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eavnrlor.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2xjhprhir.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2fhnedhod.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oilxtvpd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2uprgknsc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gt2nluxyjdz.html


<!-- 参考信息 -->