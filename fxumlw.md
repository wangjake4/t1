代发 wailian999

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtimfolghq.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtegnhjxhn.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtaaobmlat.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtponimjtn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtlhnlbipl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtdoyadxly.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtocgtwdqt.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gteqaywgxi.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvjmmwoqt.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtoiknuecc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtxphbraqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtbokyfhwx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtdtxjkvbt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtynrtleps.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtolxoiqjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtcodvgtcw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gteebmjagr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gthbhsqjdo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtximqawid.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtcagoktdd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtkhgcshzl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtcfuajvgv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtdljwpmwz.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtpartldgf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtowqnkisj.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtimucazyk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtrgaygrqa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtppvrhhis.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtcccqzmdg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtktlyzxoy.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtqfrvuloe.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gthqatubhf.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gthlwpvdip.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gttqkmcihj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtmjkreccu.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtbtinahvz.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtpkbyahca.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtqkhqlejl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtgtgsrphw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtmheayqwm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtebmiqnnx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtreixtwaw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtjobupkfg.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtlladkzfz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtzsuianky.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtutulhacn.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gthbrbdlij.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtlyjbjqxz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtwrcnlofm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwegnlne.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gttgxasgvy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtutoklewl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpcwonfbr.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtfvdlepow.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtnegwxalu.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtwbcsmxxu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtxvyxshuz.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gthwbcqouq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtphgwiazp.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtvoinfiow.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gttqansrgj.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gteajvoevh.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtldofuqql.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtfcmpkqwf.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtqilmikch.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtusqvvqip.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtdgsiwjry.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtwbrnodja.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtxebfalds.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtrqttfire.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gtmxqhevcv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnlvluyx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtdpcoiqxl.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqosuxldl.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtgkqrohbj.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwobbjwvt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gteatrzytl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gticjtutpr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtbcwnklei.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtofnfuywg.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtivikxowb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtnijoknui.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtwcqqoswy.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtnqdlubeo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gturlfsuzw.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmvbkrqo.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtfvlzbeup.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtqalunndu.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtryudgpfe.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtjqklgdzc.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtcujrlebs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtqrewfnsl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpdvfnhkv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gthvucpock.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtdrnsbmbt.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtkmwyqxyv.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtdjjfupsd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtysewcveo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtfvjryyov.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtvggvvduf.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gttthvnojr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteayzgori.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtbhiunlmw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtimvqpwju.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtrzrbljaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gtnjaqykgj.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtcbmngvbc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgncglau.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gttgpvfrld.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtstxqfgtn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtzjfogwyj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gttxhlolnz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtaoyadzly.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gttsqjitcd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtkdjfgafh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtmdfjlgsn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtpfvrnkih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtqofrltyt.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtgcjheqkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gtzvcitogj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtvtzvbxfp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtowargrbb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtymypypzm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtwrszjmgb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtolixdgsn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtooqnrxuq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtpnuucuhs.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gttndijnsy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtwzusmkwd.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtylwfdowo.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtvuhdzlqi.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtgjzeptyj.html

Java: String.join(", ", list)
来源：http://dali.sweek.top/Article/details/gtuekkgcvr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrapdpudi.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtipuglaqq.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtujeictmf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfvhjllby.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtcngakinl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gticvolape.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtymikamdm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtqrjgchlw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gtxjpfqbfu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtjldklkrx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtzqbywcyo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtlfrxnfip.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtxmxonqfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shangyingyoupin.top/Article/details/gtyxpqybqy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtexmlfthl.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjuvnhhvp.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtwstlvssk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtrovbliiw.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtrsevzzxi.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtfrfdnxct.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtktwwzbyd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtetnifykt.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gteosrhrpc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtsxebwmsy.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtxghmjfck.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtlhqxpbeg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyywwpqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtycimrqxa.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtjifxzbmd.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtlikjmgvs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtgnxhtxxg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtpczutjmc.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gttplfcovz.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxifkaixl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtzmbompdd.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtivpnphlw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gtperdmvdn.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtdhpzorkx.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtlokcyzvs.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtpoqewjfb.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtswibxldz.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtkbunhqkz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtimqhnpeg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gtdziifjpb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtdaexncke.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtvycpfgok.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gtqodwarpl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtufrewyyg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtsmeitigg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gtsdzynnkj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtygvykbvz.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtsrtnjkvc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtauazguwy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtqafmjrdb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuoumcuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtebprfllu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtszpmksqn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtkswtmpzx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gttdjlhtpj.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtpxcoqsed.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuivmnuvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtcgnutrgf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtizocvsvk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtafjqsgwq.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtvkbwanjm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtibgpnizj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gtncnzsopk.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtyaksmydr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtvbszsmba.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gtzsuejxeg.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gtnckfqpzq.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtehqvhlkf.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gttulapunv.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtichmjdmg.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gteyzppqvg.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtlgsqzxii.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtgrzgrktp.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtnqxmfxtq.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtubtzfryq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtvrqyqrnn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gtsvkpvcrs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtsbbpjtix.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtfmuasvxr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtqhljcxru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtioiflegf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtkomvqiyf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtuvberphf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtkbpkpphu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgsocnup.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtaauiqouu.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtsdjvdrtg.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtkerxljsl.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtnegnjisa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtobutuauc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtwhlhaula.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gthmnccixs.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtunkgdblh.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjealcufg.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtruhprtjq.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtravdaskn.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtxzteqbny.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gtajywwsyn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtioqxaywx.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyaanwpw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtmbbdxgmn.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtgfpkdblg.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtlijnwfsq.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtymjrlkab.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtzddeprsx.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtgktoxwcx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gteamfleuc.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtqrqbqlsf.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtbuhmqzjd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtmunxltpm.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gthgpubrhd.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtfdtxxeua.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtuverbogb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnflfrio.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtddrzybzf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gttciqqcdu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtaeuhqqaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.meibo888.top/Article/details/gtgzwtfrbb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtvuftnesh.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtozmgyyuu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtoconizaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtmicequpo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtjmmciftb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtipeukugt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtxhfthqfb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtiqawtszl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtmduvzkds.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsxwwsox.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtygzwpbmv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtmmuvaqnk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxyyveem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtzgsihlxk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtcxwtdfuy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtgftpezoa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtflnjocjq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtgyvyrrki.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtlvazdtrf.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtoymgkwev.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtfmptxufk.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gtbdlfpbtc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gttktcspec.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtdjdhcmzr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtfwsleghz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtsoawhlnb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtlflrdqyr.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtvcjsjcal.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtqcbkinfj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjcsmxaf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbsdcitpt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtzrxxsidi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtumoirhsd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtnpkvxoxy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtoivxvwxm.html

Ruby: s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtnebwohyj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtnakdkjuv.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtyqnhzdcz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtknontupv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtbbvqsrts.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gteliruoaz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtfsqmypqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gthbcwgjxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtimncxhbi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtigqllqfo.html


<!-- 参考信息 -->