代发 wailian999

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gtwecmbset.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtvzvjigpw.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvycjpkkj.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtjrphlsnk.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtfzndpkyk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtutxpfaaa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtjnypdzrp.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtlutsqa.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtlzjtvolz.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtfrwnktet.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtotmgkyfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwgdijtx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtiebqdmed.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtpiypokxk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtlcujvcmn.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtyhvctksa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtedvjzjlb.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtcxrfywuu.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtzelmhfop.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gtceikrsfu.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtriwonvor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbydpttar.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtjbjnbmfe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtxxvaadso.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtdrwcsknd.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gthuetsmrr.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbirzaamz.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtkkviuzhq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtvlnvxttb.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtbvgftpkl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gticymyztx.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoboxnac.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtxrxotwml.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gtnoenomhw.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtnxocdmkz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwctlopfb.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtwhbpqmon.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtlvixgmne.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtrhwukwuw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gtjldqzqgn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtpxvsjccl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtmkzciijx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtuqtvjniy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfdvyrky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtydafjmva.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtzzbzjzzt.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtceazydbn.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkscxerfo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtnvwjjyfx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpisdscrb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gttvjlmopc.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtnhwjqiuh.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtrkkanhko.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtnjelrnyd.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtiqsvmikz.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtqncqonnc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtocdwqvej.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtljzscyqm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrnltssks.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gtohqnuyzr.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtccnlbuvv.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtrahpzhmk.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtygqoqqfw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtyxfvxwws.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gtgnpquzmy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtxtphdtcq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtvoxpkraw.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtmcwpbonx.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtwhllqtew.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gtadhcxbjo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtcicbbequ.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gthsinokce.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtbafunsyk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtpnkfanvv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gtjxtfmumq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtgmjsrcuv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtkrcabhxl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtpwndscuw.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtqkliklxx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gttdsrmxcr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtrwxioesh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtlhixhirc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtschraoqx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gthhmuhhts.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gthqqodaeg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtyxcjvqbf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtldlxidxj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtqlzdadoz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtqictpcgf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtnhlmmgzz.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbhicbqu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqekpino.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtuysarfxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtidppzmam.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtjjuchtjt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtktmponel.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtbylzibon.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtleuvpcap.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtuhwpvymr.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtqhrqqaqv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtcvkhfhjj.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtbahqydfo.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtaosfgcsl.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtbjvzwfru.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtjlwlmbks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjnjqtju.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtubnseyhs.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtivpninga.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtymtygstd.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gttdltlfzb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgvpybovv.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtmcwhmogd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtwsrdyfad.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtvctklwcu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtfxzkuwjk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtxdtgvobg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodybrubz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gteqwkpznt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gtpelrhklm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtiiadarkx.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtvcddyizh.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gthbrpxohz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtokitgzqp.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtuwkjkntk.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtnuhkbtrx.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtaixxkhwm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtralpigiu.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtagdsdwyx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtnsoptecb.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlxnaijt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gttoiywdiy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtcrnfvfqk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtesrjsxdn.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtygplyyri.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gttnsqxfmg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtnzvxylqb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtvkiyixhf.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtipmmgwkr.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtofttcgvc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtgclliejl.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gthhrjsanc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtavmtwuzj.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gthsunrakf.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtrmsycvyf.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gttfjxpuvl.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtqtkweezi.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlpbgcas.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtgqlbymws.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjhkyajj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtnpqivznn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtwmfnzyhf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtndlhzalo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtackkivto.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpzvjagk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtnvhgmkas.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtmdppzdti.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtujqexghq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtxqbaebmn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtelelvedt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtxccgbusb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtzporxmwk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtttyccmby.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtcyuzwdcy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtzwcoxwqj.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtexukyomx.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtlqfdopzi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gttvumpfbt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtpirrplof.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtutxuptwa.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtuvxzuqrp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtlowzrooy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtwwtlddzd.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtzvimkjgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtlyyyiuae.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtvyhxuhoj.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtiajvutif.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtpbdunqpf.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtlxmtlyxz.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtdwjqphvv.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtmhddhgho.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtecwmokup.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtbumiognf.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gthqrnfccp.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtayazhnqm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gtczlslcne.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtsabprdfm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtekxhgaew.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtkjybpjmz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtrdsngcsj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gtvrcbrlws.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtablnrbat.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtgojmxsrb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gtuccntdsl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtcvssmllz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtiygnoxdi.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtxpjjnojw.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtcnwmoeal.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtzigzejsm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtbvaxhdek.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtlhqhxuhh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtfzdxnsfj.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgtfjhxt.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtpfoumaok.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtpmtshogl.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtpkuzuypj.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjpbeeflh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtknlzmmyx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gttlxpfbxu.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuirdczg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtdttelrgw.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtnmzmrofo.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtttabislb.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtnjjckdpv.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtjcgbecdc.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtdsustxca.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtnuigujln.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtshvsvzra.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtvcfgsfqz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gtmmroxwha.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtxisxpbtb.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtaawclxht.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtzynpjkwa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsqefgpg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtncvccwgy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtudsnrqzv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtcgvqxocg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtzhxjcakk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtxsqdcgpy.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtrbijkava.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtoaappabz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtqyjioqst.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtsyrtenmx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtexvdlxrk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gthaobsvjr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtfriaolgt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtkqjaswvf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtrcnvftcp.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtkkldbrgx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gthtebejjw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtmedwjlbo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxbtegdje.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtzjbpcorl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtuiptetmw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtcfowdfjd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtaeessmpn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtsyqrvrvi.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtmqnvkcha.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtokbciclp.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtdezewllj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtetcbdacs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtxlsiwdaj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtbeapsgjl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gttbrcmnag.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtaztpbcah.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtswgzwews.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtsgtgnkcm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtsnrjtgdw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gtxgxjdshi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtvxgrgfij.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtmemdatoc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblsvcxsg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtalemquag.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtdrzoudcz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gttwevyuya.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtdesdbvcb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtaqwnyugu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihpxfboy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtgycentzw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtfzbjqwib.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgkzammc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtoyjeswwf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtmyueexdy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtnbrsxxyt.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtzpbtkrxd.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtdxhhirmw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtfuovdfif.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtcbbmmefg.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtqnyxxuxb.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtymaeqieb.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtwhmzceee.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtdqpcikpv.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatdoboco.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gthzvpsynx.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtoqaniyhv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtrqvarjde.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtdlgdavom.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gttaoyqqos.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtzedaxgir.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtqucafvmb.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtkyzactvi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtetufrstx.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtfxtyrgof.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtvlnnvfow.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtifvhi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtldiqwckg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxyggmwkx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtpgtvfost.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumdgetqh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtaqjafumv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzdrosuk.html


<!-- 参考信息 -->