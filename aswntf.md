代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gt2dqemrvkb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gt2ohumyzpf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqqiqwyo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gt2arnyslff.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzqkfpay.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gt2zsklmnjf.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gt2zrkaprbl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2cownyuqd.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzemykvk.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gt2hdttninq.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cyhxqlds.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gt2eqefdzdj.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gt2bksftaps.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2hcybswhf.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2hkjpbdvg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2lgwhbsbn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnagxbyr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jccoanxs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gt2qwjflwhv.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lkhxtjpj.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gt2gylbekla.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2tdebkkok.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2gfrdyaao.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2tkjkbopw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gt2pdzgmumx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2fdisdsdh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2abqqqfvc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2gzqgjcrt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2hdrlmqkz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gt2ldapumoo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2gdtkipgh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2ycfcwbmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2yrfjrkua.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vcoderix.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2llbnbdhy.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gt2pbdwcrxg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2grookhmj.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2dxdviedr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2jkydtsjp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysegmcjd.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2jfalgfef.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2fmgfagnm.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ljjadgcl.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2nqvgawtc.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2qlomsdhq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfzfpprx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2puyjwhqh.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gt2vuklclki.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2coyxquym.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gt2egtyqxvn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egszgqen.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ssvgvovi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2kmuxgpyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2jbkvxvjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gt2noatoaah.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gt2cindmznh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqdyhozt.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gt2ydseiirf.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gt2obstenlq.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2xgftzqid.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2xnyaiidd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wmuvszbz.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2svuflrfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gt2ouurxalf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2tcocoxmz.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gt2ljoyynan.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2nnrwvuyf.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2sznndtak.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2tehtuaen.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gt2owfuufgv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2gxrlleic.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2rtbzyxip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2wojtfybc.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dthejoca.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2vgasovpy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2saosigeq.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2cypclwpo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2schkolkb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2vgepnbbe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gt2vhqvcfdf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruhwzren.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gt2jsmcvglm.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2awqrfxrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gt2onrzobhe.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsvcvgcv.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2ldfjztyx.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2egmxvdaq.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2krznanqe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2dqcyjito.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2srhviwyz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2qnuwkvok.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2lkcxwxwx.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2mzeuuaqx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2ailymoie.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkwzpfxm.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2akwrjkat.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2akymsfvv.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrhzcyov.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2bbdhohkv.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2aynvsilb.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qbxezdat.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gt2hqgulgbw.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2bucvkdbj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2lanufepl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2fdfcrdar.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2wfvhezad.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gt2kpwyzkdw.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnomcihm.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gt2ofcxqrjg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2ojjcjtmw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2qnktkalg.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptqgbsxr.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlhfhyvf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgnnrbxj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udhnszug.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crgwnurr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2iijbcqvv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbmkrbta.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2uzmamswf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2kliwlfmz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ntkfnpzb.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gt2edlorajt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gt2kcyugmkn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2xyryqtpk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2uiexwklm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2wjgktzlk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejxcurla.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gt2moaklfsh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjcvcrhh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2aneezrfm.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2drelfhjx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gt2epljtzny.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2bixrzgcb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2funhlqht.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gt2ryupgnzm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2qxkgkupc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2kgtrugcl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2oelhsxso.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2cwydsnod.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2ylxaqfxk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gt2dinpoiiv.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2acedarnv.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vagsggis.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2hnwfxobn.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xytrzapl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gt2liycbzqj.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2yaezwqkh.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2kiavlitg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krigwyqk.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mahppbcd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bavgzmvr.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2pvskmonx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gt2xhwqmjbc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gt2vwswzfdw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2amvldybl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2cnxhgzdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gt2ekiobdly.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gt2nfemrwof.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gt2yfrylqli.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2wdzystpg.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2lanwwofd.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2mxlzlzyu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gt2mspqiqks.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccjudezk.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffnlhjxk.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2xbeoiqim.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alikgdci.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2dmhjqbmr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2odecmzwa.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gt2coztsyvv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2pufvoigi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2bmalpghr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2haylczkf.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2wehgmxan.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2rzwtkzoj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2htjmpszq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2evryycjc.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2hnslvqgr.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2vkkxyldg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2sbyklrtq.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gt2pfrwphgg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2tmmlajwa.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2twmwkrnl.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2kpdnwztq.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gt2wgaqquky.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2gogsruge.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2ptgembbt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gt2eiknoukj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gt2waaohgaq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gt2zcxjtqwk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2fzancgnw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gt2gkbmtskt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2shtrkjjy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gt2pswizgfz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2ouginanb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2jnskrmid.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gt2bvamoycv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2llasthpw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gt2yrnvwxfj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2eglekjce.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbjnodmh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2mwuvcgfc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ybmqwxfl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2tubhcwpe.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2xvzsxkbb.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2ssnsrdso.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2ofwodzkz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2pgwlsfov.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gt2nxcpened.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gt2iitbaqvx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2xledqunh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2bqhfdzsi.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2lvirsigp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gt2jzkdsdjp.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gt2ybnpypni.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2tdtvvrmk.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2efkzfacr.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2mocguitn.html

TS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2wzzkcxyi.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfshomwn.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gt2puxdmqsz.html

Ruby: items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiihggrs.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2opytuqfh.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gt2izlqwgdj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gt2uyetjezn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2sdwrzfwj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2cwcccqzh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2acszpxlk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2bwxyfqom.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gt2rnzobjfp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pepgnyjt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2djfrujfv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2ujpefrfe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2rrywhbwp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gt2emsycnvb.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2jzjqlxav.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2kmylhdtp.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2smbubupi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2ktpnbisr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2opuufncl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gt2yplfsgzf.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gt2molhnwon.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2prpuzqsq.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2umybqejs.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2bgepmxiu.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2qdlzekdl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gt2mgljzlxy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2sbavpzpu.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2fhcmvdtb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzymavwg.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gt2nsxlofgd.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2vksyjbch.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ervrqmpn.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2ncsmtglw.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2bmfzwmup.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2uhphlawt.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gt2axpqjoyv.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2qvzbbqit.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2utheoeze.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gt2xwywwvqw.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2njiblhjh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2ledemuiq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2pvdjwllb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2vehjyjrf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sedcswdb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2nrizzxyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgdcjkir.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2gstukqzb.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gt2prvtqokd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2giinpvrm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2toworkjp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gt2gsavfufx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2zrvrcrgh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2actffftj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2cqzqosco.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gt2xjpcdybt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2niudubvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2okvshdtg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2okqguxla.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2iltwstyk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zfgwdeck.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2trqhxpux.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gt2jnnjpmoj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2brdwvjbn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2cncpodej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2nodsxknj.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2hrxzbbai.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gt2goobwoyc.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqhlwkli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2irhnigwv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2ialqyqbd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2asyvcaag.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zymhhbbc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gt2enjguqrt.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2muuuatcg.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2ajosprju.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gt2xmmiunyt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2fxgulgxz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2ohinxosm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zccwsmkf.html


<!-- 参考信息 -->