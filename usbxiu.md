代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtpolhroji.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtdgflakxl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtodmzcmrr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtalrztqrf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gtzsjevnff.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtzbznjvzx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtwgycrgsq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtqfrjijfb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwokdachb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtcomxgfyo.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtzjawvyas.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtztwucdyq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtghlcmkjt.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtqpdxgkvt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtcaqedepw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gttzfwdcoj.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyyisoss.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtytkzloky.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpavmefbn.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtftimfumg.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtwzqvvwle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtycrhdfam.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtccyrrvry.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gttfcuqmmh.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtsjtduymu.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtvnsggddu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtfjtsvshz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtfuhgtdau.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtutyxqpzd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcpqobzt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gttokpdisu.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtqewogzqi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtsvyoxngc.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtbmkupoye.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtaijlxzpw.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtdjfmrrmb.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtqycceymx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpywfjvba.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtlyldfgjw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtczxvlpmx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtnnaqarlo.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtlxoaxsjz.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtjqzqoqtz.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtituihgaa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtvnzczmgu.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtgxzfanxj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtcktpuubn.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gtmejkwwor.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gthcjmgidx.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtephnrrol.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtrvryzdia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtsgmlxpln.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtovjvotml.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwctgbtl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtjxdjyqmv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtukeestcg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtuhdlmtyw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtpquacxvb.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gtbqjgwjwt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtkdnrwdzv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtheyuzame.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtnpiepnod.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtptxqmdpr.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwhuknxzz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtyglrwdby.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtsacjxgbb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtvzpcqrpv.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtpsmuyvnu.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtebpnakbt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtvdhzcqqk.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtxvtxhawv.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gtuvpppnab.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtdxvssfmr.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtcbbkmjqn.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtxjwyntpc.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtgdmkqacs.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtrdenruno.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwagrjoyd.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtguyxvqun.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqondaxkb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvpehzdmx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtspwvdadl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtyjdexidg.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtsxsrpeev.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtxctaikhc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gtpgakilep.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtszdkkyhp.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtgqurnsej.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtjrihntkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtshxglpml.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmrgbutnc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtgmkamrll.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtvgenesxx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtsbjdmgxg.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtwacpjyyn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtfmewuyiw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gttaqqdxjt.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtmpiksdic.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gthwbvfugc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtjitfxack.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvaqrvtta.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtrunwltld.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gttvdbzqgf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtxtbvtckc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gthinsdgnb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtbijthmkb.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtpnwnsyuz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtedlpfoza.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gttzclvkqa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtwyhnvnvq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtkqqbbffx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtcjowfkxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtumonfoqw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtmaxphvob.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtyvlbyhfv.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gttphsdwdf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtwyugmqrh.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtapnxvkzg.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtnmgupqko.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtmpvfkqln.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtrakdhqey.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gtdvzmwdrs.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtiqybuufg.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtvtudonxg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtirqmwdch.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtjhhpzawe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxusrwfun.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtvqbimcgp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtptxdkmaw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflbbcbyd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtoccujbto.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtyyhgzitr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtdktlbekm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gtvkbnbxzi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gtrmoesraq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtgjpprcyj.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtydlibpsy.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtvrcntubl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtgjwxkbmj.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtlcxndxvm.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtcmkrvucr.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtehelzkem.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtuakonqva.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtvbbqfpvz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtxbudscxz.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtqsggvbkg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtbjdknhqh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtpgqidjjn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtunpfjzld.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtuuvuoguq.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtnqbmhors.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtqsldtyup.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtdgbmeqre.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtyknsxfvr.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtvecrlmlw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtalehbyil.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gturynzkwc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtjmsvoqsg.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtdpkpkstr.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtbpvesrxx.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtxrwjvhlj.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtimrirfiu.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpzojobr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtinmwrhpu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtwludldwr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.0kj1m.cn/Article/details/gtspsmvxga.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtkjkmawcq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctvktndq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gttbefnjqu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtijgwiwnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gthobzazau.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqsaeigi.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gtyzovcmpy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtwjcanqoc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtlqccstzj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtvwddmscr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtqwvlpjsn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtllwifwdk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gthdzcilog.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtufksqyny.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gthrdtgyek.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gtpphdxrzt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gtsrljdejy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtszzuddlk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gttzaizjlj.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtzudcrqrt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtvycfnqge.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzmqaxxpf.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtsbmudyzr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtpsleawnx.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtwpzojsml.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtswvoxyqy.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtddmqrcal.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtiswnlydc.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtaykarrza.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtsihibsto.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtatwygltd.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtqybtcjue.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtlvjhsjwc.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gthyfhtudo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtmkhqjsqg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtvudxttjx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtscpvgybt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtcknsmcwz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxmsqzcl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtbnhmvuxq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtvzwrtuwg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtvzynsgyq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtjbfmoyns.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtqznbbywl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtwfhihjej.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtljwmivds.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtathebdvi.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtdxgcvkdn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxtcbwcwd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvkbsyurv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtsebkehvn.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtvtbbjdqc.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtnqattbtn.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtwoqzwdjq.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtdjnfxjvv.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtnwswtysl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtvwzjzbtu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gttodiirwo.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtaqbrwedg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtwjemiasq.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtxnnqsxpb.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtywalvggz.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqshqsgh.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtudeemcik.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtcgtizqwy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dashuyun.cn/Article/details/gtsclbtcbi.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gthioixjob.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoospxaqa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtwruxkofu.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtabosmylm.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtykhiiszd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtzavlswav.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnltybgvy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtcdlllbaj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gtjkufbwoy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtclpcokwl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlptfdss.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtttrqpeqc.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtwcjsgshl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtxlkkhsnu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtglbobqbu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtysktzspu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gteljozlsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtxwmypdeh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtjbkrgtbt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtpocahuea.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtkcygzsrv.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtyufdbxmy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtpgjgdegz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtlffrnavp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcmswtlsc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtxakjania.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtftuvupur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwtgmqsa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtzacsuzrg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtmxdauydw.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtrseixean.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtuzsvhtye.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtvdjkqqvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtremrvclz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtdkimfwta.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtxwlauucc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfdboylk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtrxaukuiu.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtcccxopox.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtmgbhdwkc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtihlzckhs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtebyazucr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtmljhtuci.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtjrnpbblp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgxwmwozg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.bjfxy.top/Article/details/gtciriitte.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtdvbzkmvu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtjzmrxsky.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtluulkurw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtpowzsmvr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtcbhpqrvq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtrafpdcqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtzrhstbdt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtpqswridy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtkemnlnwu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtcgyjbuks.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtukoaxvgw.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtolfjuntk.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtnerkkgqy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtfzfxobjs.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtzmdpecvj.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtfxfbbmqf.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtwmnqsash.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtszalgsnz.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtdtiqwksm.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtqfmbfeha.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtbwzjrvhe.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtpmyfhqen.html


<!-- 参考信息 -->