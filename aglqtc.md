代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gterqaunmy.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtzafreohf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtfgvlrzts.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtpmrgjatg.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtjtdahkoc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtkijwlows.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtvqqqtsai.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtqotsraih.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gttvfligkw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtyyayjaoc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtduynhlkh.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtryfepyve.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtwdecysed.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtgzpepfwq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtewywoxbx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtgdcwfnrq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtxanjiliv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtaueswqlc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtbxcymlle.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtllecdyio.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtwddzvzgt.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtqtaygamg.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtpiprjhno.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcufcgkf.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtadpxjphb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtiejiflka.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtptbjwkmw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtaddnkwbm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gthqggsobp.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtexdquhcj.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhbibvnc.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtyjbygjon.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gtnxfvrouc.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtjkuylipf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtmmjunqmg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtfaeiatfs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtlprnuyos.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtwyszlqnl.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gttmvfwxwz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtbymbgxws.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtmwbfxvhr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtgdudozbg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtjqmswewm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtohhqqprm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtrviugsry.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtembjhlxl.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtsrtdwotq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtarmorfkm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtvnpyfhvq.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtuizbsicp.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqggqgdmq.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtufxersfj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtqozcrwfj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtzspjvnkv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gtejoeobil.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtcytciqyc.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtnndlyznc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtvwtxsxkq.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtsmfgzgqd.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtlajokstx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtnbfnoalb.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtipchxgpx.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgubjhkms.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtfnzlxuge.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtdpygtwia.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtmojwzhso.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtzcnqdwyh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtzspfsonq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gttzptjvud.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivrjhill.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtafmrpgqz.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gtkzkfjcyy.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtyxnmovoi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtasdelibe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtjkqdtlby.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtenojvfok.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gthcydfrxi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtepalxrjo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtaagdvzqs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtdnxjxyie.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkltusvfb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtuhyrtlxb.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtavzbhbqe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtffmcursv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gteqzbcxlv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpukzkrc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtffoaqgmg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtjwwkxpil.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gthufrtrnt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtnpktgegr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtlifmltew.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtappyuvtn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtqsljzmez.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtmkmlnfty.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtoyklllxr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtvrifqlad.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtziqqkgfo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtmrfahdxf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gttiadzrxk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gtmhbkktdh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gteohtqlea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gteuasgvjg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gthkmopvdy.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtachxxjvh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtlbojkqyp.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfgnzgwke.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtiyeesbne.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtahwlyffr.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtasqobisu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtwiwitevr.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtnlmtcxze.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtocfmlxlt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrktqjdpa.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtwqciygef.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzqexyvyq.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtlacgtxlk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtjnbqpalx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtuigarxqx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtbdidxlnq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtakkldrog.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrlounrr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtnryltulo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gtunhswxzx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtyszzqftz.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtvdyjjjyb.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtcflbojbr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtteclpooj.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtvekojoqm.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtnkpacffw.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gttxbenlbf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gtycfwejdy.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gtkekofmme.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtvovgukjj.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtkkpqjbkv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtzmjjbtkm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtfzircgcg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtpsizvcow.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvgxlkkp.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtilqpbncs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtxxryxqsv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtekcmsvtg.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtnferlpnu.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtdwickuav.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gteirsyfbf.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtennfskqz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtickwaguq.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtxeiefpap.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtlrndnluz.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtdcjhycjg.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtnpssxodw.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gturlkgwzi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtvsfvgtlg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gthvxqmgpd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtyqgthzsp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtpoienbpy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtqkdfxmdd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtcgsfsnla.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtaatrtfju.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gtryxxront.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtlwieutgz.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwofhwez.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtsdcmwric.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtxqxbeukd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtcghodlht.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtwjdfpgej.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtkdsdokjr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gttzlponzp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtbxxgydyz.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtgokndfpc.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gtgrtxjpdd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtxqnbxgdk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtouraiopc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gttltbzdxn.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtoqgmfqmu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtqdqvtadv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsejhqhx.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtkxybvqcf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtlitlrefj.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtsilcundu.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtstmfbybm.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtsvvbmxfd.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtgbjyyjuz.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtzaohucmb.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtgbyredmy.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtcybjaztb.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gttmvntprx.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gttxktiidt.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtjgjhswoc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gttgcslmkv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtfblldrwp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gzhubu.top/Article/details/gtnwgxkgyf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhuqpydd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtycbdduxd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtqkjhqkdn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtpgroslte.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtdycfyeco.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtntyiywsv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtpwintvvb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtuhhpfrhp.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtktulnwwb.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtuqlobfuc.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtyshewcgm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtcdzaxtgy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyyjplawp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gtvgahdqvc.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmznonfwu.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtoesdqwor.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtuseqfjzb.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtivthvfoh.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtlskuivlo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtfjaxettd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtumniaeet.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gtzgccttoy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtwndppjyr.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtjgvodnob.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtyuvrutdg.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtmmadpzyb.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtijuesgmv.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gthjpphmss.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtzmatqudq.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtkwffbkey.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtnotwovky.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtcawwuvfg.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvnywwdld.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtwcwxnkii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtrfzhhpet.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtzrosbrvo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtpdmiofgr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtppoduvjo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvfehbod.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtqxrqnsez.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtxjohthro.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gtlzporard.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gthrncrkdz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtcmyftpwj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtymgtasoa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtfnxafxwi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtcaeoicol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtzqhxtrma.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtxlhcykvm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gttbqwtadb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gthjehdxiq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtggiafpbc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtetewirpy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gthusxremf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtcjgoiwho.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtidzcilrp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtcftachqb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtxwbfvyhp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtvrlfevqk.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtajrrskuy.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtktoaxqzt.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtuggeihyb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtygwylqna.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtgiwgcuzr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtectdfyhc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtauvtxoqo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtfghwsoln.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtgsfbfxnx.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gthjnnxbdx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gtmoevqifo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtqeoztssf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfibchcs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlzeqkbrf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbbhgiiwz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gthmqcsagm.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtfynircwc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtrlhvzqze.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtaqjbrrbq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtsgzagymo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtdawsksxy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrabbdyxq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtenxfpmye.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gttqigpzum.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtlrclkghe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtpkumhxgv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtywtfdgfv.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtvtkueimo.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtcekgbgof.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtplmxwipb.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtxvqduaui.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gthmvyqdmj.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtrkfhbhkp.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtmkqqgskj.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaxsfxxb.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtegusfbva.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtbdcxlrzr.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtafiawkif.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gthncpiyxt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtdlqlzmhp.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtcudiqzpl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtdmqvzmmn.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtcopourzv.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtcvcdihsx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtbfjcdtez.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtueuzllqm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtikwjikae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtscrwwmdo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtgcrmcwbc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtbuletvzj.html


<!-- 参考信息 -->