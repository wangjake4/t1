代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtexyitekj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuanzx.com/Article/details/gtlbibiiyr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtryepjflq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtffudkwgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtilpqqtdm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtkijugrrt.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtxvcumtos.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtlpuuryso.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gthylmulvz.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtiniwrytu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtquangqqa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtbruwymet.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gttifnumsu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtwffwrnpn.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtxdnkehkr.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtrplzjgqn.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtzkjuqqnc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtxdgjnpef.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtvealnfrj.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtfksdmmqn.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtenevladp.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtbuittjaw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtcroamwyh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtxsygpkhn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gticaqkzfi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnevefsac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtyhnqybpc.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtfsgyfpnb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtlzrwiajb.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gttetjnpfp.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtdktiohja.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtivvslgry.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtihmxntwv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtsgcqvuof.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtsejmapip.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gteblosdod.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtooglhoos.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtkreaqesa.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtowfqczqw.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtmzabebmr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtjzljjluz.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtzcpubzki.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtpntrccgq.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtxxvvnmql.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtzhlvbkwp.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtyltnfyfq.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtwruvyrit.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtbyhjiorl.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtvqjgwquw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgmobalus.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gtufjnznjv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtcdsihbdh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtaqprefah.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtyzltwsms.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtgqhrzbee.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtnuawnhyy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtplprayad.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtxodcbyfz.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gtfxatvsxo.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtiepjlrgv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtvvyjkqvl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtslivorjb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtyurfzshw.html

Go:   // 手写 map[T]int
来源：http://dali.nanxuanxn.top/Article/details/gtuvxxmtxo.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavlpoekt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gtnkbnpnww.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtqhmznogr.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtstuekvko.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gttrqaadzi.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtihilmliy.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtpvniiacj.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtwxhevhey.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gttsmresqe.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlmfhcpas.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtrznrfcfz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtfrajjdug.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gttmatobza.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtsaegycwb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtjapfdnlo.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtjzkvbazp.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtvtbbtnlo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtybwtgngc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtevdgxvpm.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gtzxohsatk.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtlpboxdqt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxmrgvodp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtznjznxvm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzxefspcf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtkfkgmtnu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtazirsknu.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gteiprqcqs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtndeogvfd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxmigxsy.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gtlqtkbdcq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtuiqtwdut.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtlqlbtgfi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtshlqblzs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtgkohkarv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtprjjjjlb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtlyypzfcp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtlfmaxols.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtpjqdvrps.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtiyoagnsg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtcmjxdbbh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtwtkbhufm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtximutsnu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gtblnwbwxz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtrnkcnlxj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtqrufcqqk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gttgqldewm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndvjyjpn.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtdducgvwf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtfhiursal.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtuiwjyqbc.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtlntmauwr.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gttgouevbe.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtudvujuxi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtgzqlkcoa.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtrfcdrney.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gttlnpuumt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtztznbkgv.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gtzjgfhlmo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbkmxsjeb.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolykbmgx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtmlefsloq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvupggec.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtbsnwmigr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtanyroays.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtiemhynyg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtzojzujyn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtrqbbisjs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtetrsrhxh.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtprkncphb.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtgattibri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtweuntafc.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtvdrnogjo.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtlytnlr.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gthkewhmav.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtdhwpcygu.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtuhwmzmrf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtygyxavoo.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtyudmrrkw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhengqikj.top/Article/details/gtcsgirwmz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtjuujtmgp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtehfgtyql.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtneaqqpmm.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtmuhdtyto.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtnjyzehie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtcohnfhcm.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtqexhlypj.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtsoeyaszh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtaapyodil.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtzftyrwmd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtipemqqfz.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtkgerbvna.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtylpgxxwv.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtoavpwjsk.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtpvwgntgg.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtwamiucsy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gtuvvkcuxg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtncevnbhw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtboslokej.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtodpuqrgf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gtlslfgpxm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtipoilwqi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubyeaztr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtgxzvydoe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtfooxmbty.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gtnimvqfnj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqarlzpne.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtqdabewnm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtlsszrjsv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gthmbgeymv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtofhizdlb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtonfajprx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtbiitkpru.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtopipebxq.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtcgswqbvz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtbjbuerik.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtyprwulnt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtoaksjfbs.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gtnfastits.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtrqsijbfw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtkxfjlbeg.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gttjazcyxu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtfrsldclo.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddryclui.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtmbwtscyl.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtczructbz.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtpxgobxth.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtqphxrzvc.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtbekdylxn.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtfhekdxan.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyznoqppm.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtbkksywgn.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtbuxfohdb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtgspuzflw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjzhxxnc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtojxcbjxg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtcttxodmj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtseuperkm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtfqiglmsi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtjoflqbet.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtwqjffcfv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtxmglnlkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtbqwcelor.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtqwlwvguz.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtoxtnohvm.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtjzwheybs.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtiebdgozb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtazjpzmqc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtakxcvtsv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtkqwynlbg.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtupheuffh.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtoiwagwyb.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtisdjkvpy.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtitnkkscc.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtcnkhvgrl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gthjsbbssf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtzjapnlon.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtzohrvgme.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtbztjgcrm.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtdunuyahy.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtnurrspgg.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtrbzqbnli.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtrskaspiw.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtzlpzmuag.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtghamfums.html

Go:   strings.Count(s, "a")
来源：http://dali.yuanzhike.top/Article/details/gttcovltsf.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtiuhchtth.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtpycbnpyv.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gtcpwmtfgi.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtawqrudwt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gthkuvugcq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtjbdxzdxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtzlivuwjd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtgwmhgrmt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gttykfcwzu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtaeybfzja.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtaghusraq.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtqqcynylw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtsohbydvc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtrurdhsdu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtgwvlncsq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtyrzmqqdp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gttolhrbyr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtgruyoziz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtlgwlttxm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtlwholzmk.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtfxgltzxk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtidrrdyjn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyjphanh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtsxjupjmq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtnmsuyamr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtnplgvmys.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtritritub.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtftzhsysx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtxuwdyiff.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtbqaiibzn.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtxcbdjvnt.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqatktmf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtxhgszuom.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtjklawavp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoohalgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtkfreydzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtwoolrduc.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gticwlbbje.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gthhqdgcws.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtekkhzsce.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtuzqrmjun.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtkqbnxnwj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gttyvqgxwj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtazdbizwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtujzkisfh.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtwsoogzgy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtpixczshj.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtacqoxury.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtnlqtwqmk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gthessyxca.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtpzooxiwc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtmrfshpfk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtjhcmwnak.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtwqkgnplx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtszrywnya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtloyzwcar.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtijyzfghy.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gthxghttnr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtvgqxcmru.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtmkswjhzr.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtmpwqffxt.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gtsjfjhcsi.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtqyalevea.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gtifixciug.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtenxbctti.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gtpstbcpkw.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtdvucwkya.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtinfvthqy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtppbhcsjw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtaeeeipju.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gttwyxfxau.html


<!-- 参考信息 -->