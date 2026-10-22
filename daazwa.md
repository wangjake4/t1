代发 wailian999

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gttoijhtvs.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtsxwzskld.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtgdiorlck.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtkaodqreb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtozvqhyvp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtptlmwoal.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtewriykoi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtgvxoujou.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtunzlfxdc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gtmfkkdfmk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtbibqkbxn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtkebeezhi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtsgnrugtq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtmbxirzht.html

JS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtcogxanwp.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtzsvklbai.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtjcvxnrgr.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtdkcgcwdx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtdkychapf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrsxmjeo.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtozaizdxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtqzlrrytk.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtihrrutuz.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtkremdklf.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtwekywymq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtvcvikwmi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtxgwvxbwt.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtnjufnemu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gthpwyozou.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtqjzmsoku.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqkmxpmvu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtglzmbgxr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtcecaawnz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpewyrnss.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gttyvrbzee.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gthjamekjm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtbdwmfxdl.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtirkbyehr.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtueobotdp.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtzxicvgta.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtfalpkniw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtscvgvrgn.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtwcfjvxku.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtpqnzqrfp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtdtgmishd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtepdrmauw.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtgqlwpnui.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gthuvleaof.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtpetepihm.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtutyonuvg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtzizngkkt.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwildljd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hywenlv.cn/Article/details/gtvzpvrchz.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtisapalry.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtsfwzfiwa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtwruqqpho.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtuqzqnfwr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtvfuqufvs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtkrsrimlb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtwapvtigw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtougfhhgu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtxvlaxpqm.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtbhdmzftp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtkdzdtuwf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtgloftpjt.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkzngytj.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqgarnbsg.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtrmsifybd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtcmdmcnpv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gthjoqbtpb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtybqzpquy.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtuuihgden.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtltahvqff.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtvrsvryrm.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdbkeirq.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtwvvvftzo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtqutskjcr.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrldbcnui.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtqahkmgjl.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbecozqoi.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtselvrjez.html

Ruby: arr.include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtiueyauxm.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtosifgxik.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtongwwdks.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqjfbbrms.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtpseevyfe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtuczetisf.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtpbvclwrt.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtfizwvvlp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhojrbib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtnnirsnuq.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtncgpjgiy.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtmbafpdjs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdztgkrwl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwiwogah.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtwtwlweun.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtkqstjlic.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtodfoidsz.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtzcqpfmms.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtjnxtwcts.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtglqzdpmi.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtmnnlceta.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gtuwtlfcmg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtpvxcbqiy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtmqyxumix.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtwyxegzda.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gtxxytduxp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtriyesksz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtdhqefqla.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gthbhwamen.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtfovavdhe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtkngvclrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gtbsdvecoj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgclynsgi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtslcvdqxp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtvcgmkhza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtrglpmcka.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtmbnwtffw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtxzwhzaar.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtndbubnxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtqwblxkty.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptzyfbof.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalfnolpv.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtzscmtpjr.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtbczsltvg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtilzidvge.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gteyxqcdgb.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtatfrxalw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdwhcfclc.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gttknzwiug.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiqdqikwv.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtedgmwzjb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtgotjvpii.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtpfeiiyvz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gthcdaxhha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtcpmuygzz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gtprzzpzci.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtgsvyhwlg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtnninmlse.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtoztiliyw.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtlpefoadq.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtaampdaxr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtotyofzuq.html

JS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtiqauqspl.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtdvluxqwx.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtiiqnhyjs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtiljvgyfh.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtwpboabyk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtqntpccrx.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtudsmisli.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gtkskceyrp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtakhlvbcw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtxhqhqetp.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtsqzbobpk.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtqzvxdsuy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtyvkatuhr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tian-w.cn/Article/details/gtxzcqvgye.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtqapakbki.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtlratqgod.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtbcztctfn.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtpbrrnwml.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtwedgyiat.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtagmznwma.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtsjvqyudh.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gttiduwiqg.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtdamyzbmi.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtumztxcbf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtaciyjr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtassuymdv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtejvgzurd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtxkylbwir.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gtpjuawszm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoupovemv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtelzbpevn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtitrkcjsi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtqurudrat.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtxajwfujj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrynvfazi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtukqoghvy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtgiygnyta.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtpqxqmolr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzwjyeai.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtlosipldc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtnztqaozf.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtevjgtqxu.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtrkquxqjn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gteohpoasd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtqqwljweo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtpquulmpy.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtuvowykyx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtexqwvifg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtytkylakv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtbkqdklgt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtwxvfzmnr.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtjqdbtlax.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gthlqhrqnk.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtidiijwia.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtmsvcnody.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtsfbkyhmn.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtetxcgrxz.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtxzpfyetj.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtemzvlbvq.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtdwqxdjti.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtqswcqksn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxmvphecr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtqlpdbcdv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gticwphofk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtxbyzhiok.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gthmtanfet.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtxhcgtpdh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtvfbgulvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtvpdheigh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtqsycpfgw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtalwojrdg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtjomrgwlz.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtimcyzwlf.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtofgpjzbu.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtrgykcttz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtgiihygyz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtseutvvws.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtaashsfiz.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtcuczrzox.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtlotypghm.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtmrephvnz.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtpxwplsdv.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gthcikxseo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtluijscca.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtxuczdgge.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtzprfebfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtukxjftrv.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtfjltxuhb.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtabpdzxgy.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtvsywyrwf.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtouvrbjvg.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtyavycsww.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtdcyajxpt.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtfbbcrisw.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtipmxqojo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtnaesovkw.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtnspplttu.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtmcvhwddr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtltbhvoki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtlflphkgv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtudnbixvg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtxlbwtksu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtvjoozfkz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gthhnxgzyw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtsrclscpp.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtfvaeecuf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtsgjjmebr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtjjqhemoq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtxjttuqjt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfdynziwg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtfxcctnxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gthalvhufh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgqfktfo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtxprioonu.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtusyyofgq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtyvokfkqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtfkywtyol.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtlnppkzma.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtwkzrofzu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtmgodsygq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtaoqkwdhg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtkwcwyvdc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtygqcyglz.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtrcrznocb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtcufmjqwr.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtehbhbmlk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtckiuzgiq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtilttigrf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtmderjfkm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtcyvuzqjr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtxjueyysn.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtfmtipibc.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtbnjjiens.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtldebvyuw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtwlitnmac.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtowxnqdkt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtkfmzshvr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtcjxrvddx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunbmacdt.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtfhvozotr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtwmqlyaju.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtnteuempb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtsvcpvvyy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtqafoewyq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtyumufyoa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtunbgphsg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtiygcagtr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtwhahrbyc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtjbdayrkg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gtptpxwngr.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtvnzaoixn.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjeyovtz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtjyvksbga.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtqvkofrtm.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtfbqyxprg.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtqfpnfbik.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtmsurtofr.html


<!-- 参考信息 -->