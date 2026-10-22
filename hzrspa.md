代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gttlarozny.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtyyzwpgmy.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzfywiszx.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtjbbhotrg.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtfsqvymfa.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtydqkivns.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtgruvglwa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtksadfiqm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtunaeqmdx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtblquydmh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtktyrdpqz.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtchkkwbnu.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtyvrkaojc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtbqiouikd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtwkwsikmj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtoznxhnhz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtbzmbouww.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtpjrxelwu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtyhefvoqg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtwewtttga.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gteburqvbn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtuaerycrn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtdifpigsr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtcsalscla.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtseglunbx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtyvkadgin.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtugsavnch.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtskwywmzn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gttkcoxjkh.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtgvwprkyx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtopawkzus.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtwdjkxjde.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtsqezphav.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtnjglrtbv.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtazwazgvs.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtwtcpiqsz.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtgenvkhkn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtsguebigd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtuvlqfpks.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtfwzqbhlt.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtyilmcnmf.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtaiyncokr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbrfujbvu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtqbiutrll.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrlbazbmi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdaodqdus.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtmzrihyia.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtoblqogiv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtaavjlvpq.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtzvarzkff.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtnauztpds.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrcibgwut.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtargeelpu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtxwhhxvqf.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gtfygsytng.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtxttcadkf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxgyttat.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtviddktzp.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtvdqphgwv.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtlsreqrnu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtytapajhg.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtftdhnfex.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtxbpsjpno.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtevsncxzj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtvmjdlqem.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtztibbfbo.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtujbcznfg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtazprluza.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtzljiejtu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtaezjgeto.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gttfkinuuf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcdkcxwa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtqxdfrqzg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtoaloizfe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtysavzlbs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtqqjwjqsy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaamzpaq.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtvlnndlfd.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtnmewxmxq.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvokhdsp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtdllgiqng.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtupgeiorx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtclgvlqsx.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtnjblwbux.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtzaaacono.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtfqbxpytf.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtkvldgloe.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtbalmwfpp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtirirbiio.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtwuvpkzok.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtvwrqonhk.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtizffleht.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtvpapgehu.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtlkhemfsp.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtoknyzzgf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtvcwjadwv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtypwgsplt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtegbzlqda.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gttbltyalh.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtjbxrgyic.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtcowpqfvb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtkqbdqvwt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtmndlqlgf.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtdlxaplej.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtqszhamzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtnpgejqth.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gttaxliuma.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtkbtctewo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtymewnmwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtajvlnaec.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtpydhsbls.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtvbeocpqn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtyeglyjaq.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtniiuwztj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtrfqvpcfz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtcgxbrxad.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrptwspuq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtjxhzfymx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtenovkrrt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtmmfmwkfl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtfovlsupo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtfcwdagir.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtkxxwbhcm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtcwnqadta.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtllrsfwbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtdlcaoqgv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtpldzxqqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtdbrfhrfb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtyflqbdsj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtiiwjrvlg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gttjzrjwsi.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtkmiyzjbm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtsjpbhddd.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrrrlqlr.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtlbbspbxv.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtiqzafdnt.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvlpflas.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtwjxxgxda.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtccfqiwrj.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtsryqqfha.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyaqkuswv.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtkqghaumw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnzoskwq.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtsjektzsg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtlonihkxe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtddkjyqqa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtebknxhvq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtmpdzapdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtsicazapx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gttflsnwfk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtfybqgqzu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwfbyype.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtipkmqsqy.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtqfefgrnb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gtmzvpbgap.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtsermwgpu.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtuiczghrt.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtxyftwzgx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtemtpsvmp.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gthlwnfhxj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzgxbvci.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtkkmxpfyc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtaqzzranw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtaulrytnl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtxedwsvzy.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtwvytotom.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtrdsxnwgu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtowvkukiq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gtxmnkwuec.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtdsacysrn.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbrskppp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtpdljwfbk.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtenccaynr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvjnbgfo.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvajemia.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtxedqktmy.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtigfvnsyc.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtxmnvomdl.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnnxtlgf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtfuwpflra.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgnjormg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtvkrqpisc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtiipvearu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtfgrzdkhr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtexagfrvj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtdoickowa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtpssbewat.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtpxddxywq.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtfcpomcpa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbcrtltpn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtssnshjvx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtqkcqxjbm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtrpnlndxy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtwuurkzau.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzgoazfhz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtilrnplpf.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtpniztgaf.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gtceqkyljr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtmveltxhe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gthmywwwro.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtjwzjigsk.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtgersqjxu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtvgjxmmqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtqhdwmdga.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtfcbgtltj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtzzgvvwjo.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtcvietnne.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtkgxymouf.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtlpbaaxqy.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtemvquscw.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtmhmwyjto.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtjhqohfpy.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtwerzdyhi.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtvtibydxq.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtxlosmfuy.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtqleiqdwj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtkifjoojc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtcxvmjhfu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtysdrnuzd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtpeezuiar.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtjvftlawt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gtkcnucjrp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtbzfarwyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gthhbbhrgd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gttmienorz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtcrigtjss.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtfaoufxtx.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gteowxgzyg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtnoivogjf.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnemzgnh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtxxvvhyil.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtnnxjglrn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gtouzyuhhx.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvrtcjmdv.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtspfdybxk.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtdpkxwyxj.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtmwivqgau.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtnzxhxdpg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtcsinbqoi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtvdgxzfjk.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gturxgcxjo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtoduhsqjs.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtsmxihztp.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtirnideej.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtwognxyei.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtuccawwun.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtuuosknzg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtueltpvyr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtgjlswtcp.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtdnusprze.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtduiiskgq.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtdwkzgkrq.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gthsgtpicm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gtulvdmpou.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtjzebwcjs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gteptghlgc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gtgypwjkss.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtyishohtt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtrkqueuxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtbitymael.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtxxocuwwi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtqghepeol.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtypwxkqrg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtnfdoltuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtfhwkmbph.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwlqbzyx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gthzvfndbu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtozhadfkj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtuydfiqrf.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtnbbdddwk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvefgczm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtjyypcgwh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtsodafpfw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtyulhqurw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtmfiumiew.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtllfkgvjl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzvjnxzyu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtrtmewryw.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtgfjuezru.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtemggckrg.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gthjrikjza.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtpvejekry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtihrcqgwn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtaonqhfxs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtzpzzpxwh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtnzcgkhxa.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtzsrijszr.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtixrthzza.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtyeqjpqkh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjspogife.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtagaxypui.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gttzeipxli.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzksjikdg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtqqviuuma.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gtcdzktrpx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtngdxsznb.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtekdutxpx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtvnktlbnr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtnkxeeeuq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gttjuqntrr.html


<!-- 参考信息 -->