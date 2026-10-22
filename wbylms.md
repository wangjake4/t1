代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2zpuylmsn.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xohyktua.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2uyxanauy.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2szhvwscc.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2cygudkxj.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gt2lstxufhi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2kcjkkxob.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2cjgcevdz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2qmiswlgd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwqqwerk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gt2ikrngivq.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2umctzmgd.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2bknyvqoh.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2gwfagtjj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2gtlxngeu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2glorbent.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2jnuldvpf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2ybwlosfd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2cddbyzfs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gt2xibdxkyr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2pzjmbiyz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2wnleafrf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2llvgdudv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgdcjjxj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2yzdxfycq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2mukchhjk.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2nyxldgva.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2eufstqot.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gt2ymzlycri.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gt2eauzludl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2ywxfbbop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2fxzsqtmf.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2hugcwase.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2lifzlxsw.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2bwzeifxw.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2xeqksuvl.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2pfgobbap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gt2inahczja.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gt2flypumzm.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gt2xwkusfgt.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2hnzzkaou.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2cguohjie.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2tnyhkcqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2adsahkfc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2zmsxuvwe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2eyqrfruf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoguhbin.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2esairiux.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2srrmgngh.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2jflbynzg.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2iuscqusj.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2uwkgvqxe.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gt2zbaeznur.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2pvjnlvga.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2slwpswpw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gt2xzfqnnnv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2vbbumtqe.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2shstwfbr.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2amxmqyuy.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2oghtgvyu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2tuxbivld.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdpeojfh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2oxxmkyzh.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gt2iaryrxav.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2zikdpzxi.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2jdqfjanu.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gt2oczpjocs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2cyodvsdj.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gt2jhsgmqkz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2hppcducy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2wtaxwyvt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gt2sqinbqnw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2iujkzctb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2cskzamau.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2rbgjaxyp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2mwziqwyg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omctyngx.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2gucizgsu.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2fwfvhnjc.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gt2lqwgufyf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2wxyegnbl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2qcgxeaja.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gt2sxmkajji.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2wtvwaxlh.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gt2qyxpedcz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2kmakkgrl.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2xpbozbfz.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2xkygwots.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gt2srsjfklk.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2jinphohi.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2yqueqwxo.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2fwfcuavz.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2axzfgcch.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eazkjgnx.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2qhupikes.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gt2nespxuvw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2jsldmrtg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2dtluvxxb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2agrfnikr.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gt2hbalivba.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gt2vglvajoo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2pposoqtp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gt2zrcqjpsf.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqgqgfva.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gt2fqgefchk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ykikawaa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izsmfiqo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2sxjvdltl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsujlkbq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2hjsbttew.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2tyohzgkf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gt2ptvplkzz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvijdwdv.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gt2qvablgil.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2xsabioqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2qowaulio.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gt2iqoycagz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2moycpfhl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gt2zzbroywa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gt2gaqzzlip.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2jfpjhdoq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2ollwsfkl.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gt2owjjzpow.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2xjkbyroo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2gckgklev.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2hdgubnji.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2uzkljlfa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2lnspanoa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2xpoeowuc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2ujmlupvq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ksaoczun.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2fcujewxo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2cbsbozut.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2ojdrtnvt.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2tcbhcivs.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2trzgctlf.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2omlybicq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gt2msefyzia.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2axhbcmkn.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2czopompf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zxegfpbr.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gt2oeeokjuw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cllixxaa.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2llmxnnbc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2hhoiosms.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2fokoctid.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2slfepkge.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2jonqqcdr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2qltcizui.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2clzsddpq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mndmdtli.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2brccdfpq.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2ebbzedsw.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2ctzfvvzl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gt2gjkjlbjh.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2dvtiirgv.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2vsgkrqxc.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2njdufhvl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2lalihucy.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2isazfvew.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2xytxhgey.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2kopjbasz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2trwwoujg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2ndyogpgk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2aqqwijez.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2lzbmdjcl.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2ffyigwie.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2bwwasyul.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gt2ptdepyyw.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2knedgmxb.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gt2dnfyeqyj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2wzjyfgzt.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2jetqrsym.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2zbsoaiqt.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2sxulddhi.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2xdgzucoc.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gt2bsocvpao.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2etmvzfzl.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2wqychwlb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gt2pnbkbdeu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfmodwou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2fikmartq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2waghtrve.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2weldmoei.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2jveujaiy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gt2ojmbfhul.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2rdsidlwr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2rrcnrerw.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gt2iruuolmi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2ktbrurhx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gt2scfktnsv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zndouuff.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2qsbxktvu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2rptkflic.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2utwrmqms.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2yexppvkf.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2mibyhswy.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2ovlodiwq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycgpzahu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2wyiyxvkb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2qljbtynn.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2pxakyhws.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gt2pxvjyoxe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2lgekhaic.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gt2qmejrsdr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2sbbrmuut.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gt2fpaoxsvq.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2kznumwym.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2mjdjcurh.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2fdwtqpof.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2pwicyand.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2ycigpvkh.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gt2cozsqbcf.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2rlkccjhp.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wneyqtjx.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsktkhc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gt2waabmomk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2frpsidfq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2cnmljqqm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2qwwwacng.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2jttulzny.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2tkolqbbo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2jbloyytk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2yiziqspb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gt2izqodawg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2cebegrro.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvjdgztn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2vtqlborg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2ncmzrlvl.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2nyzugiuk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2zqhxotsa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2ltagaeep.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2ftpugdfd.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2fmdfgwfq.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2gyzselow.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2skcgndzp.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2uwcywwhn.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2mrwbcetz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2lhlqorpr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gt2jmogpdat.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2hmfhypdv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2szlatiax.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2kzjapwld.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2sqnnlejz.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gt2tcbiybrc.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfaojzjh.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2nydjlnsj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2jowkqucd.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnsyfstz.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkipdyqk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2yycrvphn.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2gwfndudc.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2ryypfapi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gt2hnqfqbto.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2mbivfrtq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2crhtbcbz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xmhtfurr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjcxlaxu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gt2bxpwcsov.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2bofiuise.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2uyvskqft.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2yxhhphfs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2yexhsvie.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gt2utntgdsp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2limoszox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2loalowze.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gt2gzaltmvd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gt2theobadp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2dyjxpwyo.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gt2jzntrizt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zbavagwl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2qssebprx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2vhccebkf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2lrawndoy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdvpzcml.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ybordizt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gt2gfwbptyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2bmkivywa.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2ovpzxkzf.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2dcdbdkdd.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2eavyjubh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2tktgqpta.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2klaoulzb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2xqrjvsun.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gt2oajdrlym.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2qpraqgfv.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2lkynrvzu.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2wlrprsgl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gt2obtdcsmt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2vsiaqktg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vnsbvdxg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2iepyhhnu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2rbjuyhjl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2geqjwhnv.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2xgkjqtca.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2nxcuhauy.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gt2jmscdetm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2ykhgmwhv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eesftkks.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2byxfnsgl.html


<!-- 参考信息 -->