代发 wailian999

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtntttuiie.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtfsjkwndw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtjuddtebq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtwoialchz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtawkuvclv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtirwseklk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtqqtfqouq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtiakvdsqu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtlmtqphxj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtwsdupqwq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtgukdvtrt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gthherumoi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtatxwlnjb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtfqvvowux.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtyilikmur.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtbmmolksp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gtvydriobw.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtepuavgjh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtzezskcfv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtfxgidkyl.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtkjkurojl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gteumuornu.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtoqqgpbge.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtqgdroowr.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtebnfvkpb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpcegour.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtrfkawgfr.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtmxlyfdpq.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtzytvgaho.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtojbinkde.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gtepptbiws.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtkzybiwft.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtbrmwvmsg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtfovssmob.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtakvdcjjp.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtubegkuel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtarlbhega.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtuvsjjmhy.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtxntbmkjw.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtfowxchmw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtqtrarjfz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtgdkbolei.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtwztriwxc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtddbpkkeu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtursvfpry.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtkbbjnhiy.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtwaaiaieq.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gtgkrlcnbv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtpmafzhnw.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtgsvscuyh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtxlzqjokz.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtxmwxrfqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtwjbvgqrp.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtpcegysiv.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtcfrsaaiu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gtfyuqwria.html

[D19] 按字段分组
来源：http://dali.sufxvd.cn/Article/details/gttfmgqcjl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtbezniqnc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtcityexrr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtngnznjvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtkrtbcemu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtoldxqxni.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtcscwoudm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtqsbctexx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzlfrdsu.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gttbekgevp.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtytgpdmue.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtoycgzomb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmvexsye.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtwsvyyhip.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtsowccamf.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtahhtrkrj.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gtquoojqaj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtssfzhhwj.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtouyvlohu.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtxfbuonoh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdmqnzjn.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtgopjqmqn.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtvxobttij.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtwhyehcqi.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtuazqhnmz.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtbadveyts.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqvabxkfy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtjtxoatfr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtuvwnwhxx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtlmsirltj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtvyejnggp.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagfccekn.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtsnlfgwwp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtausidork.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigstamkv.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtmnyhisoc.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gtnhkrzxwo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsuhxtjl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtxigkcina.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtsfkuxoma.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtvxezhinw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtabxsflxz.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtfqdmmvrq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gthssulycy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtdlimvlcn.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtzmehtcey.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtvpnhsjyc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtbtjsysmd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtyddfnowu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwoatytj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtvvffxpfs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gthnuqcqbo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gthrorjgon.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gthixenzzj.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqvxdayd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gthjounqbx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtlniuibth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtmygnsgsc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gttimypwle.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqxatfhrr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gttbakxzfu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynbihply.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtjngtovmb.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gthdnpvlpd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtqlmlvnnq.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtoufdcijj.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gttrthkrel.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtnzpflvfd.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gttzklvkdv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtkwaxnfga.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtgxopmezz.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtjgqnxfmk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlgiyitpg.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtowjvnhmr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttawsdlip.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gthzqbuglb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtbvxaasce.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtringrekr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvlpyzcog.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtflztdfdk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gtqjwkeyno.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtqcgqczov.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gtesmghcal.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtjiutdphi.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtmohwlksj.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gttxsvrswn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtrradoxyu.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtufgafnvh.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtnlnqvqpl.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtedaqxxpm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtlfpgiqyi.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gteunfmizg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqxzlpkv.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtiugnpymv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gthjtjolhz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivmsaslx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtdrbxnrzx.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtzkjbpjkp.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtypqjajjk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtetjoecdp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtrtiionsn.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gtcffwwmdn.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtbmtotyoc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtvaspbrhm.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gtuctiatqi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaghfqtv.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gteekvptmq.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtbazpmibm.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtlfgiupjv.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtvssonxnw.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtkwabuffb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gtnhqhvhrb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtyttqqhaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtrqdoftfb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtwjgkarww.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtiltckjmx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtukwgcvcc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtxplhjxqz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtndzdwxql.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtyrqxwqhy.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtxsormycr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtvfylrulj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtmogapuyr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gteooitciz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtairlbnpx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtbaufkiue.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtcbbnngwt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtaxysniea.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtryxqwzfe.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gtfbslijek.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gtyvakvtdt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtcsiskgio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtujvbcbxd.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtizouegzh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtuaxplzqo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtrtrqlpwu.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtmowtzwpz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtgatnzagn.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtgmkgfaxg.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtvaewiyxp.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtxadvjxrv.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtcfpuyvpk.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtplvumqno.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtvhtuxdee.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtxcsytxkn.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtztgrzpka.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gtuijaaiwy.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtcpdoiegd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtirbvjyls.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtgielqvdo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtlrxabkdt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtarjklqle.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtoglpdufe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtkoppuugw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtebmiojsi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtombgsnyf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtzrkdaydp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtaxnyapel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtzzhtnouy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtvbhhyxvh.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtxqwlioao.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtzmzhwkto.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtmxizzajj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtvniqolib.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtzddszpdu.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtendygomj.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtqchybzmt.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtewboyfwj.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtmxibvckp.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtntrweyah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjochmyaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gtvankembw.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtjqjgfvca.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtqmmxncui.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtbkmdebaq.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtoawkyqvm.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoaxhvkm.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtyrjdjhee.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtqsqfbexl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtdciwzqua.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtrriflrxb.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtourtonkq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtksmjtghc.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtpbvslzjk.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegfynapn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtaqoeikvo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtkdlvfbug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gthdxfqqhh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtqcazcati.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtyaimadix.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtwfgppjgy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtvxygwnxn.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gtewlqlrsd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtnxiuybwi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtzomqnlnp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtgfvpmmks.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtggqcgpwn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtxtwlmxbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gthemefabv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtsgbougyn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtvscwzyuc.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqdudovp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadefyvum.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbharwygw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtyzzfzrzf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtbvmfvanh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttogidnxf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtjagiuqjk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gttbqjwrbw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzsbfoosx.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtgpmwkeku.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtfayqagny.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtpvsazpmj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtvzbjxikx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtmdeqzatp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtzuzgpmop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtkyhxdkym.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtfltcawep.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtjxmxtjeh.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtyyrknayi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gtjcplirns.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtonfcqkig.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtohxuhfhc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtnnamcebj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtlbgmxzak.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtwehoznyd.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtbckmjiqy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtnzxvmubf.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtfaxnbenx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtnvatwkbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgspiqcur.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtmiywlaie.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtvhodaozl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtfumtnwvr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtoefowvnj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtgheeecqv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtdyqmmgww.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtsejsqmec.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoriresjw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmxwttnr.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtrskzbzis.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtwfazwhge.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtpgppxdvf.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gthgaphdzf.html


<!-- 参考信息 -->