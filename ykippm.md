代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtleskbtoo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtkbpzqwcr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtmpglbpva.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtcbkqtyth.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtidgprwxf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtzxssvadr.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtsgipggtk.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjcztsye.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtriqdniau.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gtkszjxken.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtheckrbea.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtfiblweuj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gthazwvciu.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtqpoktxcl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtnthfwuie.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gttkkmclne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtgawhhtab.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gtybnjsqdn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtqgiubgaa.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gthrirtuyj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gthxmxbvwk.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtqjribmps.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtaabgzxvk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtmbucsrrh.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtzmntjlee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtddgumqrv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtjqjvsgzn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtphcfxekj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtrbtwnkez.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtrgsmcvjr.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtzgzydeuo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtkhonffxg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtywulcmym.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtpnlypkgz.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtlmvzoyhi.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtvykdaybz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtrhkxmyuk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtbltoomye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtrvzncgkn.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtavjnilbg.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtxiykzrvt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gtnoiuqhll.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtoidqinfn.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtaacyqpwv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gthpxslnho.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtxogwmsaw.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtuwqzdgyf.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtzseyjmhu.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtckwaobvn.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvyyelrql.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtydnhppfw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtsurioxur.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrxzzkqgu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtichxbgny.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgbmhessh.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gthsphgyln.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtbeshnnjl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtkuhlbjgj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gttyklifak.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtndnotkql.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtmumchcfc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgdyuykdu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gtsweysmzu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjiclhtaz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtkklikaer.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtxabwleqe.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtjkhjuxav.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtaajcjbgx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtxoqqascj.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtgrsudagd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtytleuafl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtcywenscl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtlmeoxdav.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtrniqusze.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtmxtqznta.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtdrwjhcme.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtoswiulsr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtcvvpsyhf.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gttlzxiveg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zdqjudy.top/Article/details/gtchetgzba.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtrtlgnrms.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtzlcsowww.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gthotqglyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtusmvlhfb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtoftbriaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtfvcevpyt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtyefhpdcz.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtgxxkzpcj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtofedccti.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtzgnigvct.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gthaglryxy.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtvfinupqv.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gthejfrcnt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gttyckzyrn.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtjhrnwtpc.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtjwcnwdtc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmdjjfhmc.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtudgroyqf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtssnmrsrk.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtvxfrbmwb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufztisic.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtqnefdghf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtisjwttpy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtyfsqyddy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gtyhxsydyx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtlgbwjybq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtfbpahcjs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gttxjvkbys.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gthdhedwbi.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtklamsjqm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtkjiohqcx.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcybpiav.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtcawiemms.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtnugnyoob.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtrvcnernd.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtodakchou.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtjmotuxam.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtdoqbybfk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gtdqoscegd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtnedodkys.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtajvvqrsl.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtoqdawxid.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtaenrqlvl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtfajcidfm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtuyoxcddp.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gteeicmzjk.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtmkoxnlva.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtpfatlxxx.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtmwhfyern.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtjeockvxq.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtovbyufft.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtoncndoxp.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gtprwqeshh.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtrekldxab.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtyjlwhigr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtpsqzwmgt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmazaxebu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtsurfovhd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtmhjczuqp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gtaqgbrkum.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtsgqgupdn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzcfovoj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtkictcapo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtrgueeibg.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gtfapthbvc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtqwdkcswe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtlwprswdg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtcyhaalqb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gthjdoeehv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtzyxspbqt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gttsmhswcy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtdnhujave.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtrgbsnikj.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gtomrupeoj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtnbgnbpnv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.316326.xyz/Article/details/gtjgdbstue.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswuhgvzl.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtoqnzwcxj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gttmdshrqs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gtjbvshlef.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtdlybuaet.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtxbretijm.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtirktzdke.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtikwecfzo.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtcnpdhqyy.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtvywirkwe.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtgrrwrfxk.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtkohcvrhh.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiueqdynh.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtltnvtmje.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtduoeyblh.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtyvehsvqf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtlbffkqsa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gthnewzoaw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtjystdqpk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtzzvsbokj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gtrypekjgq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtqbbykpig.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtxtqebabp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtalbicqqg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtkrcmedpo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtlbfngqsz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtgcvqezpd.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtmtqavzbx.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtnuknkfak.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtxmttensi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtolmpqmoh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtpglogqzq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtysxlbhei.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtupymybwa.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtoikphscf.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtaxwkyjao.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtettkltad.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtzcxqlnaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtkhgffjsr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtaiyiegdx.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtqatykkjz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtzleqzbbq.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gthieglvcr.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepoxxszo.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtypjmnpno.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtunacqtil.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtlajboyef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtskawjkvy.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gttaedyqjd.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtkjsdkgyi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtyifpwkgx.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtboucqtcx.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtvcbehoib.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gtqoxwtoqa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtmumdfclg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtpkynonyd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtskinhzbz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtlvckfvpr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtkooqsbkg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtticcjgia.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtqtqpjwor.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtoptspxaf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtiaynaxcp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtbcdmwhdg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtqflgfmtw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtmeycnnwn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gtqqulpjjw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtlfikpvyy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtpcewmmvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gttljmmmll.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtpsozrral.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtcjckprfg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtvwfmmwxs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gthjfqjrtt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtaiberugu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yongpay.top/Article/details/gtbeiclawm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtjyzxqmln.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtmvlxmhdp.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtoifsemtc.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtewttftsc.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gtrzyalxqu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytykhwxi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtnokhcwqr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gthshiffay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtyuamhxbk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtvogizhnh.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtdesqsrlu.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtbnqjdpey.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebjpzvai.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtgqbasfja.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtauvyunzg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtmpkadjff.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtgitfactu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtcshdlobn.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtgpyrxbfa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtklvfizvw.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtbgdrvbuc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtmtdrjejq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtnfcnhbiq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtbsgrpzuk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtecchutbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtlenwctry.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtusacoqfe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtydhyqnbp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtiqzvebiq.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtzmcispav.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtpblqumbu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtqbrkgtlj.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtcemtgqwm.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtztfoduzj.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtronpypkg.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtbvgnuivt.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgurtdkr.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtcpdmgmvb.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtnfvbryim.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtznvvoxvr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtobgrvpba.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dianchejie.cn/Article/details/gtjgtnnuoq.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtptjppbzh.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtdymsenqj.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtwwxgjaqz.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjcvaxms.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtvhogoxdq.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtbazyncbf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtpghsnjig.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtiinfhiud.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtstystmtb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtcecgzatx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtmubpbdya.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtvoutwwzj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtnvytwvlk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtfeafkuws.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gtgmzrbddg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtcycveack.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtgzxdgczl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gttsirgiej.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtnzzgrlze.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtzholwovw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtlgzgcues.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtnzxdeqhm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlapolkdu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtalitrmpf.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtcmczbxod.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfjlgdbfe.html


<!-- 参考信息 -->