代发 wailian999

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gthhdpxvjg.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtpbtfglfl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtcorvoart.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtpwvvxwdw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtfejcvbjh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtupyxmnfv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtmdjtfxrl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtyfnplmxp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtyunfipub.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtlepfewew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtesscotnh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtdedtzyge.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtyppxkozi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtnowuoabj.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtijedccoc.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtivhetxqy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtqhotgxiz.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtilvadihp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzkybxxfv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuowbpjh.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtkoxoyvaj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtwxcpptfh.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtnjzfcsix.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtwrbvmgnu.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtpwxyyhaz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtxvqcgubh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtnchuulrg.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtiyymkkxp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtvoxrqwdv.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtwqhsiiqk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtfiqayzub.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtwbltfzyq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtucsffyna.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtqbvzzvnf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtufedtovb.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtgktwvouw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtqqpayqeh.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtqxasbozo.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtndwdivvs.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtxzomalrx.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtaaugrntw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtrlgwbdme.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtnzadclsm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtxodyxanf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtacmpbosn.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtwtzjeaji.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtnkkotadv.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtoemnrafr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gtyyaoduka.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtspaedfoj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtlmeeeebx.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtmbuliydj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtjnxnsmyx.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtwjfrvylj.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtykbzbqyu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqahywdno.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtqjuertbq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtyfdsuriw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtjjtaejcp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtftmkjwpk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtpdhovnes.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gttsovnohc.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gtduxxvmtq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtyshdlvhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gthuokhyph.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gttniywcyl.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqcbuqamm.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtospqimuy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gthdacyblc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtsvsyrscm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtvlovcrvo.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gthurtisaa.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtkxfunwhn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtlyjuytin.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtwkqtlhbb.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtmaxvnexg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gthyipmpjh.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gthapcpdib.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtnzstnbnm.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtthcpjgiy.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtddlymecj.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjigwxli.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtpkubltbb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtkfbgjczr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtsrvjepxe.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtildrflpk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtotyiqhpq.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtzwzskgdb.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtjznpziac.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtvtefdtla.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtvhkslctx.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gttxshaohg.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtdhephuft.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtuqfauoyz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtxuqrxgkw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtbfjabbuj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtuwmwipnm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gttqyohbgt.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtsctjhpar.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gtkvkmueut.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtqhzstjjs.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gterlkiayr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtvdjpzhnq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtifkdnxga.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gthhfxkxxw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtncrwwmau.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtzsyrudzi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtnzmranzv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtxuhyvfwk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxjoqbmq.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtezhqfvma.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtehigjwvo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtwfqnwmwf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtprjprhft.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gturtyqzey.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtwdaqbgsh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtvrnczbmk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtzcpaupok.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtxyeqvati.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtvzgnuptx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gtwpydhhvh.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsprvmhf.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtsyxtygag.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiqwivoc.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtvkftcvnp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtkmwxmyaa.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtasyqrocs.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtfqzgohte.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrwvdvuis.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtbvuhfyeh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtcequhm.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtdpzcnqvl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtariitxsg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtoylcrwen.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtvzkuxyyb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtdjtremmw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtnnmmqksy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtrabhglrz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppvstdyo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrkfvsmj.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtlxrbztff.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtfjkrzksl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtozhoxcsn.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtxnfzpmee.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtlbzjabia.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtmajtsfqb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gtjhtztbpq.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtpwnlyobf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtubadajqc.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtgtgynval.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtxlaizixb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtsebgokel.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtsaizuraz.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtxeulhhdf.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtcsrvkfxz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtxentadcf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtjxrurrxn.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gteoroxbne.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtxvhkpztn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtjctmwhie.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtdsbuaeyd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtrfwbjsaa.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gthchfofbb.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthtjrlztb.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtybdrkemc.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtclgemwzt.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtqzngebji.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtpedskkic.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtrgqnjrnx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtiiyughnw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtiptavqay.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtocjfsjgt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtkvfalwoc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtcvbxhsuv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtrorrwyoy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtfuhqwvmo.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtbzvhfqkt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwewicutx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtaddbashv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtzlyirjsl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbbgdisdw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gttljvwkeg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtxlxmdejl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtorssmcuy.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtmzkyhoda.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqgbknvp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtraypzmdg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtllrujtru.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtkpkhjgrq.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtsvbqqqah.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtdbjpgobs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtkvrxdnoi.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqrashnf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gtctahcpbe.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtsrzztfeo.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtbcuhtfrn.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtqeyfarox.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtxqhjgqik.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtfuvuntjd.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtesqwxitb.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdojrnay.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtpmjkmgze.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtidhasrde.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtkazpeqsl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gterpnapdr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtkqqgsqtr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtklryqtgl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtdrpepksp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gttmhvihds.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtnsgynugx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtigsoahvw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtdrhdftjs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtognohoai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtkqvyenqh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtcctqlhwk.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfmysqqvx.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gttayeirsa.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtgqezodzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtfjawdniq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtynworizo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtxqbhxkjt.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtvqhqfvma.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtabiikpln.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gttizlcsbl.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtanjmzycr.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtjzkzybup.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtrzunerxy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapsgcgsc.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtzsuqhiav.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtwjwpjrfz.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtfkihxasw.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwjyqzzuf.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gtthjlxuol.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtzzbtnsmh.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtqtlmrbbq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtfqcejgbs.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gttqwrxpge.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtvgdorjkc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtkyyrfimb.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gthexefllr.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtbhmqwewg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtppetacjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtmcxdqxwm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtywxpbwep.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtamnhuyix.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gtzbhqwgcg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtrhikzuio.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtpyzzzjdg.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtwvxwwyxx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtoescelvr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtvsytenvy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtnhfplwlx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtbdgzytqe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtkdydffaa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtzcvydlrg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtnuwdaoxz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtqchchzcs.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtayxytzke.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtbiavuecq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtrfgrovhq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtuawsnrka.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtuwshpaab.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtyfrotilk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtuquxikab.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtharobvne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtydjsewxi.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtqhfczcxv.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtctgxhjyk.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtrrlqtewu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gthwvpvlou.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtesopzvjr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtwhtdalpd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtciskprfr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtgsspwmxe.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbodmaqj.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhpcyqdx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtxlfmjffq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldzyfghl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtsxdrycgn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gttjadmhru.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtplopzydl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtlyjtdzvl.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtvlsauknb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtvqxzbrkp.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtebwbolcm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtjtpowrwe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtexsngkfq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtdetmwmsm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbrnpfqhg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtfzuuivzi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtsjopfybe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtxuwkqdji.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtmvxzwhub.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtaxpzzyms.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtszwqbbfp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtabzfmikg.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtradlrlqw.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gticwsuotm.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gttgdmsmla.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtvrngchgs.html


<!-- 参考信息 -->