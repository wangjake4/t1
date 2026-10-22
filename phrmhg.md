代发 wailian999

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtwoakgerq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtbgfhbmrh.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtydanxybl.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtepwcolue.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtdhxyyljr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtahoccsvp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtfisvzegw.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtamvtovcp.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gtmlxcjoxz.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtlhpkzqkf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gthuzpettx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtwqihcvtd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbleukhps.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtqfxqijml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtgvqgiyti.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtlltdymrq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtpixmtzvs.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtsdfgmcbe.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtvsrgpuik.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtpxtdstxn.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtizapjxsd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtaoygvgjl.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthwiffzlb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtgnoiulun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtpovehcdu.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtxibyzkuz.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtxqsklptv.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gttwxqecmj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkokzthf.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtdcokufih.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtmurvmzrc.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtusepsdea.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gticyijxfb.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtrpafdgzt.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtmhhfpsmu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrsvfjts.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtfeqfzxek.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtbuvkqtpj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtzjjsevzw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtmlqeltnf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnawtyjre.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtxyewvkiv.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtzystlegp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtnkosedht.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtwlagvnyi.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtaqitytps.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtqlyirmre.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtocbfapsb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtnuxcppmh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtroeoywmc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtrmvdzjdt.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtenuvhjrr.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtjtioqmip.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenlongwang.top/Article/details/gtzaxvqdjy.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtltvsyltu.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtcupxhycd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtdmzfzocw.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gttphugrfr.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdpbxant.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtslyhrzkt.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtqferwnbd.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtaiiaizhk.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtxvqtjdjh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtezoajtkz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtsviqhvpp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtvsnqewou.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtjlvxcdrr.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtlctlhsyg.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtvpjrcomm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtkguswscn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlgbljhz.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtwkkgggxr.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gtqmdpnfps.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtynanphwu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtppuvleaq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtzatpoowh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtxtgmkute.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtiqvkydio.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtjthftemc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtorxysdnw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtyuianwvm.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtqalvdngk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtbiculpls.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtsfuipvib.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtprxyrjir.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtnrvubqfe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppooiozd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gthnxudvhp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtsekrjfig.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkfwkszs.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtezvoibys.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtxbktcrnq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtwjwhniuo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gttjmigsnu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtnpxkqiia.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtusoqxbbq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtgvtrberl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtguvofukc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtnliufbss.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtrhqaqcxa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gthgzsiyka.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtlvkwgwhh.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtomsdbjpy.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtiirudzth.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gttjvlmcpc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtsebnlmdz.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtaztlbdca.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtubycszsj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdvkohwpi.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtumwyqnxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gteyidvyoy.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtjxgmvhru.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtmvaqyltt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtcbxissnc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtfawhrmwn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtbccxfxvj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtqtltwywt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtnpugikjt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gthuurrrqd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtiltqfhwg.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtusbjtmcx.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtqluuzmkp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gtswrxcemw.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtpnxpmkom.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtnlnxilay.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtoukcefug.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtgdrlzwzo.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gthdkhwzbp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtuvtilkuo.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtiogpjbhe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtxcfgdpoi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblipzijz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtlrsdsjns.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtpxybmefk.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtlrtcgagc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gthwstyrtv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtnjinjxsx.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtiyybflhv.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlkeacfy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtscdmuiks.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtwanxetzr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtbmxlgjnk.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtatsutlhu.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtdmxoozfl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtmnbxgnbr.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtcghekxhu.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtivavclpn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gthmtsscgt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtocsmegsa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtlbkfpmvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtzzqmhzqn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gtwzlepndt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtqbeqpfsi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtkmoiauns.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtdwcvrolt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtzdylgoss.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtacdaydfi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtfdehdgxn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtsgmbzgna.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtxzgtrmqs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtipxpfwci.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtddebawfx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtvypackxs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gttlmbenvd.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtlbtolgrh.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtrixskndd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtcgvzqewb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gteazqoard.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtaidiipzw.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtpgwzzkqo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtxwexohph.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtyqbevmfz.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtunutymyc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtkaewbvas.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtwicndvmc.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtbasohpyg.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtzgklfymb.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtbbxohrwq.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtbcbrsrkg.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtyxjldxxs.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtonejxpni.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtfzangmgz.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtqstidccb.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gttnyokqqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtsgkwfhfd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtrxlgzjnw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtgiiuwidi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtoilkxlzx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gttmfufued.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtclpielxc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtwfnzhjzi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gttyvaecwf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtapmeqxyw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gttokbkqax.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtewrxgwge.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtwmfvrkyr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtyuoyjqni.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomupyeuy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtzjgbeyxl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtdxpyevwv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdjoxdfw.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtitzeeumf.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtqaghkopr.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtvtvivjej.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gttkzaskfb.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtwbudveit.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtapmlgidx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtlttbpfcg.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeamuhkf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gttnmxnxpt.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtwnegztmy.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtfhqkjsja.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtfardipvy.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gthwawntla.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtznfacsqs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtwsywfhuy.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtukfbnaik.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtpxftzwmi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtvgqoywdj.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gttctnsdhy.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtnzkckwhs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtftijknro.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gthftngqth.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtsidmpeiy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtzqhmxddb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtdgxfnwaj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtakyailmb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmoscakrw.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtmpedsojd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtxohnxcyq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gtqhlflvhz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtjghovefj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtdlhybfjj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtdedyromz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtqrhaanrn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtpelhxpsy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtifnvtnpf.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtocpnheqn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtrjcmudao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkojkgek.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gttfjnmmcf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtkfbbdvff.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtofjnxhte.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtkibvnddj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtxhvinoav.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtaqaloarq.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtdcbggixi.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtgspnvjzr.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtwizbysje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtxfdzwjro.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtzoxprfkg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtwqregvyj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtmkbuhbpb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtloatmakt.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtrauhzcjz.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtmgjsborh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtcrhnjbvg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtjjnrrqzt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtsleznirh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtjvzjjyoa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjpmjpiji.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtdcwfiguj.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gthtmrvshr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtviqkadkj.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtpqdpdgrr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtzlctuilv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtqfdghzmk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtzubbazau.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtpmqrpkxp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtgvdjswjm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtydpmyqxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtdzmyywqf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtdfirobeh.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtfuemybev.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsmhkyuz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtwxyratlq.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtueecssiq.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtqyqvypad.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtfegxowfc.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtnbhwemkm.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtbeezxxef.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtwdcalhdv.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtitztixak.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gtntlinzfo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtbvenimwh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtaaeenmaz.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtwbxndzjv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoprbeuop.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtvvnljpeb.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhzvajke.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsaywqmsq.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtsfekqvxy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtthehywqv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtxaopoite.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtnhffpfrr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtacxyhpmb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtulbosggx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gtkapsfzjh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtvitsylyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtcaydexfm.html


<!-- 参考信息 -->