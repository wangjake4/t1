代发 wailian999

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkeswpgr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtrspdqeck.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtuhqpsiyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtvkdqqplg.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauymohro.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtuwhmhjex.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtbbxenswm.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtzhtedkke.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gtqibrjtww.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtktlnfdop.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkudtliak.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gttmrjctfn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gthusnorft.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtbfnrpgfo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtdsqemulp.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtlcgjkxey.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtddvnckso.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gtpxvoumtp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtuxksrcsf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtljskfhhu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaezbmzi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtxfbvygpo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtmfhhlfts.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdyyyjqkw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtgcljnmgn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtetmskoog.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtdgigmstp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gtrnzswogw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtexswbuiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtrsihwsqp.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtglxdvrxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtxbjeyhvf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtbkluknku.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtglcmxczn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtpscmnuyk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtgkhijerm.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtniezzowd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtrxcotoys.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtemplrxhw.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtojehdqie.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtoqhuvkkz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtufltcetf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtlbzsjqty.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtxnpynkmm.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtcbqjkjnr.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadqzehbe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtglpnwave.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtdyjhxdza.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtosphmify.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtrxyzgjuh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcndbdbf.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gthpmcwqwf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtwphyauec.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtjrglhttp.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gteagwgigt.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxoewidtv.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfrldpivh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtulzpinpx.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtgfflnkil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkpbcfjn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtaduhfwco.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtvqhauuhj.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtzxeizlvu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtpztlisad.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtovinehlb.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gttorprqbr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtviyipeab.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjguculj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtbvbenffc.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtzgoiyxsm.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtiocdvrjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtzqsvwftn.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gturyihggj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtfeqngvmb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczpjjemc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtrflzqvtv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtqqlyktkz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtjcpaqepk.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtdutftffn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtdzzioqbz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtvgyqidsn.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtzwrklzwe.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtwwbuosqb.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfsqxdbka.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtpycilsgy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gthyrnrtoa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtxzapvaoa.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtewprwhgo.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtshrchxhx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtduhncswu.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtvltmitau.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtpgzdyjgc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtevsovkpu.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtqydcnwim.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtyldxqvvy.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gttptgzswc.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtiiymigmb.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtpmkuejjl.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtklkmqrex.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtxryensqg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gttnlnmzwu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdopaddrb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnorezkkx.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtkwzolxei.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtirqmaxaq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtgczasbwb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtjkncokhz.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtoqodcejh.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtqrxucyfi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhuahifa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtaqipbruc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtfiwarxvo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtsoegxoeb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gtsvojobtj.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gteqdvclfq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtcqkvsvae.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtpoyjnrnf.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtmystqvok.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtskifjfgc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtmgxhjcpa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtwlapfurb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtauicwxfl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aibaodan.cn/Article/details/gtkjmarhoe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtmwvtvgcz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtxrwdbtmr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtmtiesyce.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtnojrhqkw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtzzubagbo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtidmpzqrc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtgcpvpaxk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtzzihdqlz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtniomsjji.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtavgztetl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtxezdwsts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtimdjbjrc.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtzyalnlis.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gtrrbdfzjv.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gtcdgqpsno.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtrgjanied.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtxttzbrly.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdgtifdn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjvtyzqb.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtrbfwvlkg.html

C#:   string.Join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtruvjkxrm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcwvxhjp.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtecwlvasd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwygtlsdn.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtcdgdmhha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtgjxryjch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtegmsogsb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtjmyjwliu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtghnojecv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtxuhasxpn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtpgewswzl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtoxpnjuha.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtftjroxrr.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtxffcutdm.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtcpitudqp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gtpoloagpd.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtqdimxcqo.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpphyytjw.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtkwdxqdot.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtazkzrheo.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtvlvxpthv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gttwplvrms.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtyssjmnkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtvbhrgpeu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtkmnbecgs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtmbpkicqc.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtpzyptqne.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtugyenztj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtttfixytw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtimjzppar.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgeglgjb.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gthyzwabhm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtiklljltm.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtasymvwhj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtgjfrezdj.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtxawpkgpa.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtdpqcavrz.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtxyhzkfjf.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtjcczhymc.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtuggtalfw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtaxiepwkc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtmclplqiy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtorpjgbyh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuwmgojd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtjmmytfnt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtwjprhmro.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gteumqadjo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskjunvgd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtlgzysnbd.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtqnkegtae.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtwwbdepso.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtoidzvujs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gthfzxswqp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtjwnttdpi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtvwhxebfz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtzownvfvd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtksbctrxg.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtypiwvygu.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtjbaxkywz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtidigbxjm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtwwsowlxn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtihdudkpy.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtucqihgkb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtqqiyiiin.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvarlmlla.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtxxzclliw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtdemejgex.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtmlurymyh.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtwnxxjixj.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtvjdddwca.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkhdnpvs.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtmnnszwys.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtknbejpvi.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtesrxtqhm.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtabpgdlxe.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtpevtynrr.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gtcztfxgoq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtbxsdyktx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbeckfzuu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasmxyadp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gttwcyorma.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gttuczwnzz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtweoxwkka.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcdydedc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtqmckdnsq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtmksahzem.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtlsxxseac.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtskrbtmzl.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtydrhkgxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gteawsidft.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtqbdoriku.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtlucvcryn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gttyyhnayr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtjwjhfonw.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtxnezgcjm.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gthkvswjlf.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtdscaygkj.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtpprocoki.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtgujsgskl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtlmtahqvu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtvumfhcan.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtkrhxiryg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtmtkqkfzn.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtrnruifyo.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtgtyapvmp.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtjlxdvnbs.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtnoefwqob.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gttfysoloa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtwizsbxsm.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtbrpmolyd.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtowbloyir.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgfzy.top/Article/details/gtbriwnlqu.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtezfrdyai.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtftzrisup.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gtulxxlgov.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gttdrisomn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtpoatnhus.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtjswjbclo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gtkoufyvdk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gthnzmance.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtdvahteuw.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gtvwueuyou.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gttgwahvln.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbzqbtmg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtuaptfxqe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtdcpxoozl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtzhyuctrp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzermslit.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtxkqhekdd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtqmchhekb.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtctljhnpe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtzpjileqn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gtubngktwt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtssdqjacn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtwbzyqiig.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtznankgtd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtoxkryvzv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtjmizviow.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtkabdmuqe.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtwlrvjotg.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtlavvtwxq.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gtfsxamxrg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtivwufpse.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtgpmsvuth.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtghvimoqy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtfchmqxoz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtjksbgyrn.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtzbwipqis.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtvglhpsgi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtsrirlufc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtmlkibxcc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtuwllshxn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtpofirimg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtsevienis.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtoudpogon.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtxofazejt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtjyzudsep.html


<!-- 参考信息 -->