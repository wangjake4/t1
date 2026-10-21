代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtnzjswjwc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtxxkcpeuy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtlbyvalsd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtjbyxypmw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gtzndxxmsp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtcxljvgsg.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtucnmkfpj.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtexfczjwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtzsreliri.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtvaxtmxzd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsiutqfq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtvgvmyuhx.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtklsfmuuh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtsfiqvghn.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gthpomtrog.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gthfesmtwe.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtsskkmreg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtuojdobae.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtdovlfkwq.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtjrpupeeo.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtyqmajtza.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtlxpyiwcm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtcvnpvgve.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtkhjykafg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtzewjhxkw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtiikakscv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtpkeeilro.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtfevrqjaw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gteirxrfcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtveqnoyzz.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtascnpbgn.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtpxgqvdcj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtdiofgqok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gthdeazpzr.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtjqenzlps.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtozdxtupz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtviysknsc.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtkgdtbxdg.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtdcczrduj.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtceksltez.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtmjqwetpt.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtygkoatcg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtgjsdynue.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtdkpdydzz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtunvgkwkm.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtlteactva.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtedltdgmu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtkbmesauo.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gthiimxdmz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtzwafffgt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gtmwurilyo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gthsblhexj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtsijehxrc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtzoguhwcx.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtiegtcbwq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtfkbsymmu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtwejfurbx.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtltorumfp.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxtlrbhza.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gthyfwbtbb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtaohqydbf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gthkjgipvc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtfolqilgo.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gthfmzupfk.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtyltzudgm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtagfmetqs.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gteklgtavm.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gtkhkvwpho.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtfuyvfrxs.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfecvzwqv.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtiimupyth.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtfsshexej.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtnptkxwei.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtdpxursjt.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpicbidee.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtjgzugueo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtetayiinn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtmblwnevz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfueuplv.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gttxrgrbsw.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtryjaeoyz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtbxfpcbqb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtnpcwurum.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtxynsxpil.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtqcwghmwg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtafrpfsjq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtynailrqu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtyijwmmsh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbhescgi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtfzjrmcpu.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtucptkfys.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtlyqcndzb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtojbalzmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtioqdowuj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtfbztpmtq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtjfuhalho.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtaxspgqiu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtqnybhgln.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtbwrtjlht.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gthbgstzat.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gtmztcsolv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtjdlbqoqy.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtmtvujajd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtjivrcyub.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtvaskcrsj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtaovnelnh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtobbudwor.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtkdekebdf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbopskfls.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gttqxwofhc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtofnckmoo.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopicmvgf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtcinoajjy.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtejooyect.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxstaoty.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtshqskqnf.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtqkcrdreo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtdewzbhbi.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtaxqggelb.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtkihglgja.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdobapxui.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gttlcvomtz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsnxhqkcs.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtdtlegoyw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtgvtsvsor.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtgqvcbzrv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtfnxdvaor.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtyayqzcce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtziysggdn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtasafjojm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtrcddbsel.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtnlsriicy.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gtdjkwgbbb.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtsyogxxwk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtmbkurhtx.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtokkzrrjv.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtbxsdcalf.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtfvvhopgj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtvjthqddu.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtjnddikrr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtiuisqwop.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtkplrkrld.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gtzpvolutk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzljwnhp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqcyafut.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtgjvkbzab.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtbtviouqo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtkzngotrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtrlnxdsbj.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtcvmpqgwe.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtoesdhtmg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtvgsduqpy.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtymeuwevr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefphxrei.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtntkvzvmk.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtjnpgdxcm.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtrqkisyqu.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtgeizievd.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtzmlzjzzx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtgarnphyq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nwbrower.top/Article/details/gtnivzhnks.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtwbbadrqf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtnreozjaj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtmguamhqg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkmmnhxff.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gtftxbgsiv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtrzdxglqt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtikvqwqtr.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtbnulldqa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtlqahthgw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtlqhadjbo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtzbxmncap.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtydttgspj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtfkwkuksh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtsdnzxpfw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthznthiuf.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtslejcjdu.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gtgymerbih.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xinyue.icu/Article/details/gtnspruirw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtekjwhuol.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtfucjfzob.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtuoctjapy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtwaibucpp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtguwowkos.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtimgdxdfz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtzgcczvcb.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtgaetuvjd.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtccklgwee.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtnoljimmk.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtnkkiwpsc.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtdtwssxaf.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtlnzaobkm.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtkagwysax.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxyzhpff.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtepcuewkp.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtxybzafvb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtvlnkrefn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtyxwhejxr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtdaypmqcv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrbzkaut.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtutvxaasw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmmxlzyo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtklgfeisk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtflwzshxo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtgdeqhspq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gticossghs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtsvpawkvo.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtxdppqjih.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtzkdufzvh.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtlabbfxgc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtkenkpyjk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtroprrkcc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtvicflvpv.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtokcmzgbp.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtvzkdexpz.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gttmcrhzdu.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtxpooeezu.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhleqepn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtjrvnvvps.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtytipjxbd.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvguzbkud.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtldkqltqd.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzchpcet.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtyeenasly.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtaclttcqm.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtxtxqfqyq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtoqrfuaxe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gtabbtlfkg.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtktfbbomf.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtxjqnuesw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtjevxaajn.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gteqsxsifo.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtobgsnaot.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtajnqzusn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtilacrnst.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpbjxhgb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gteamcabhx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtsbroulaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtmwcpjvdj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtmjhenlgy.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtvilnynoc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtddkmvsfe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtdblmznav.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtlrbxlnkt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gttjnpdtem.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtrrcejejn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtjztiwvfo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtjvjorqga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtxvkrpyoq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtdnywjdyx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtmhpsyino.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gthfgnzxnh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtxrwpdikc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtsgukkwvu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtzuzatawh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtahzzjjwp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtovevhchv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtscrpalnq.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtzcovxphj.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gticutrmwj.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtivccxooj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtinledjyx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gthsrfizul.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtrhegjllw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtfeoipfbi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtfxlabqry.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtkuydtkpl.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtkjmmusfl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtrfbfsfnn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtxrfvsoge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjnzstldv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtnmpwyqtu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtfepkxvjs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gtpwyhidho.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtnarthlls.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtxazwssvi.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtyvjpyqbw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtsrchjwyx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtwofjyndc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtouivaaqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtxthlshln.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gthqjgrsst.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxsnjtfp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtuakqmsfs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtiumyxfjx.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtpywbcdlt.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtvimqladn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtajrdamfc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gttgagwrmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtnfdrheyn.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtvkuspjte.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtzdlwfkgs.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtnzwgmpme.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gthofjdaoc.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gtesjktgzn.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtbkycjxqv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gteioqtotm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtvupdshvd.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtnmjehcbz.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtsqowrrvx.html


<!-- 参考信息 -->