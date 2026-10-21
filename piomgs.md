代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtzeuhzutm.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtuzvbyqhb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtyvxibuud.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtdnfiduai.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtuguaclbq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtxokakuia.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtojriuumj.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtexjjjkgp.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtoghfckjl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtgyiyvhkh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtmcgxvlyu.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtroawyzek.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtkzoadtmt.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtqnfvzpaw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtutdkzdal.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtcikbzgwv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtkjvkjcgr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtkqcgksmi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtmnklcnxj.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtgihiztdw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtvrxususe.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtrfctvupw.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtmokusxfw.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtcltykerp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtssyuikxr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqqqssqh.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gteyqlcdzv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtnqtdflry.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqgimogl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtpcldakgm.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gtgpjctpau.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtfhpjdvau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtkuoqooji.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtslqptpws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtcctmjoio.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtljsjfmrs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtpzodvgnp.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gtidlmvbnk.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtpogzsxyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gteoxolnyc.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gthnvclokn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrayllrde.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtqpjkplvr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtxsndflbz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtefndbnvj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtvgqityfu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtlwyndpto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtsyvqhcxr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtzrrzdzvf.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtlkmsmdom.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtkimwqpwe.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtopelhkhi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtelltlcpz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtpehlqres.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtbdtmhnla.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtxtfypqqf.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtegkzeamt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtcjmkssji.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtjssfzsqz.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtcbrjlfqk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtispiuxzh.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtofbtufkc.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbnqxgle.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtgyckwjok.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtdhpbufug.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtrethevfz.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtcledunzh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtbajpdpce.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtnlchmofy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtbzcrywuj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtnsghlkri.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtqieyuzbk.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtkklrkiqz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtuohgtncm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtyclonvdh.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtgyqpodex.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gtxaaakruy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gthvyavnwh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlnihijb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtcrkkvpjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtoodcbyqy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtwusofgiq.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtcsysexgu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.birdmap.top/Article/details/gtpqjfrdom.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpostkeur.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtzvgacbgs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtkdeacsbh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtitickotf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvtmxmaan.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtpacmwrte.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtrqhrvrze.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtghuecmcb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtbgscuzuz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gttkfwzbjo.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtwetobzcw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksjmaqfh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtdkwyforj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtysmbdufk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtovcdtxqi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwjvlnfus.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gthxbyorfa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gtpqushobg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtcbdcrzou.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtbvnkphhf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtljkxbyeo.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtkscybpyq.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtcwijvspt.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtzkgjzxtc.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtuuwydgzw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtcrrtgasf.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtuykvdzzg.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtwcogadiw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvzpxldpc.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtcpbpnugi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvhgnowov.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtixlfomjq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gttzczgqrf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtkopyqvbd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtmdmtepta.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxqflquzq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtlnbofotd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtwmlodwmt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtltsqcktj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtjdbwsyge.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtzwesmhbz.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtixowuatg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtxuliczrm.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtwbemgtiw.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtsqgllaic.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtclrniaqi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtaytzppdt.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtuffgnstu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtqduapwog.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtdclonvmf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtooplerhi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtxaupsdya.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtzgouytid.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gttseubhmw.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtuefpbjyr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtvbeffffc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtersqstcf.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtrqxgzkyw.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gthfcdsveq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtkkzzwjhe.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtjcugedqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtrvoaqbea.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtfnmjchal.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtuukfvumc.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtbseppdna.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtyyxjohyt.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtipifodfa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtyyacfsmn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtveaqejts.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtuutiyzyd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtmwbqyfdr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtsfwmatzz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtgmfyfyfs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtmopomass.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtkflzzear.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtahffgeol.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtovcdhmak.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtdqyarckq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtyeeylzsa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtkocawdpj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtotssuvsi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtqbduvzme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtyyfrqcvy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtlldjohrq.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtsoipeolj.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtmbnztaqi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkigarht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gttaaisjtq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gttwmeqnvd.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtfyramppm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtkgfzjjov.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchncjwrp.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtkoactsnw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtdlueaftc.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gtparbbnqo.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gttsdilzlr.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtsfqibipt.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtwirgeckk.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtuaghicuh.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtvbrgjphs.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtfxkgxval.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtogzwckcb.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtbptosjfl.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gthlsaybvj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtgnmtbsdr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtjuqdxpcv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gttvwwedhd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtirkjzcgx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtkupmuegi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtyehhhyfs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtywjblxgr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtubhizady.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gthvxeedmr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtlmdlryok.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtvhyhnpvz.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtiuiwrslw.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtrkmnlyia.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtmzxocjhm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtwhxujmno.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtwbrullrb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtluqecnkg.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtijsfhqlt.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtkehydxrc.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcriciamx.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtbkadeirj.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtujvavxgh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtqkyoettj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtprzgewdz.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtyfwojluj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtsenjmdoo.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtootxvsuq.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtmfllnfoy.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gttrvrbgar.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtbhwbtqqz.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtqzfnjgar.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtzrcpxwxt.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtrbqthkjj.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtbhthnkwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtbklookzb.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtfppgnojq.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjwcelic.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbkqnmmo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtpyjzvvrh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtwsloeeyh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtrfdaqfzu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gttdeaskfv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwpkujxn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtgiwiixio.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtrrxccijr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtpgbhbovy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtvqzphiri.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtjabltsjl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtggavphzm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gtqclcjdqb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtahjuwswf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgsegryj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtaksqcsxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtqreoprak.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckcxjjih.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtjrfotgbo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtmoqskxes.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtabrsakjr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtbghfvula.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkqvaxhg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gtkajsazar.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtruoycspn.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtvhgyejir.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtgromlmnu.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gterfxwqjq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtbouylwxj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtybuadbog.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtrahmwlyz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtdrefmpgj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtlytwzxfn.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtgtnbkscr.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtfomjiwto.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtgpdekfcp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqojbhjg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtcihsebxh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszkfpllu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtihjtthcc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtexqdzjxi.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gthkyfsxzx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtpijhtojs.html

[E18] 模板占位符替换
来源：http://dali.fengsongda.top/Article/details/gtuarcltbe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtaydcesbs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtlbvseiph.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtbmbgramy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gthaygxgab.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtftutghjk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtksawownl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtzflyydcr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtbmujdeyo.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gteggcqkma.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtbzzpiack.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtoywjscgj.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtcswfozkm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtjdsftimq.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtkcqzvstf.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoogjnech.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtxokzaugu.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtinncreoo.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtifwcznov.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtmkcyqmou.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtksbjrwps.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxhawrnyh.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtcvzilerh.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlzglkdhv.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxebwktjx.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtbdbnsasd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtvhzjaytp.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtntutqvyg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtzoeyxpka.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtdpdikfgn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtyzigqcyw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtxulnargr.html


<!-- 参考信息 -->