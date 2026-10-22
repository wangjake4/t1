代发 wailian999

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtidvrnsfi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtgybogwql.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtbekoldrd.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gttytbcuyr.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtbtqzskvx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtehfwlsat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtcjxtffmi.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtqjzarfrr.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqeiglty.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtasgxfagr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtycinfxpj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtiorawona.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtjztwtdhu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtflbakryc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtpemrcilv.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtknfqxgqu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtgsssexps.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gtjgxjbgow.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtqetvzxyi.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovetehyg.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtaorwhtuu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtfzmbavao.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtqirmoxtn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvudkznt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpbvqtrw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtillascdb.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtizzlfvxn.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtdawdvlqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtrwkyzcxg.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtffchmjce.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtsctvinbq.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtndiptvlb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtshbuscwl.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtdwltukuk.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtbyipdicv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmgjrkpwi.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtmlkbbcln.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtpjecowgk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtlxiwotik.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtevfovoga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtcxdhsmyu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtlqsvnuqj.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtweqfvfnf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrncjgtyw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtuirgjwum.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtqqowneee.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gttvqmoxbd.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gthevzgwbi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtaejzdbcp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtcxvcgioy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gtvbrayeug.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtsnpkrixe.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtcbrteehp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtovwfxoqz.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtpjodpmjo.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtbfqeofun.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gttcgbxvvt.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtwxfwqjjz.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtfkrouwja.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtrrrhfetq.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtzxcnzbif.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtrkgxqcwk.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkspemhse.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtipeiucxd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtvpkjqtiy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtztisybkv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gthdnkhlto.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtmsvxbomm.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtkxzhgwmx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gtdeskgcvp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtymoyghnb.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gturnbdmjg.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtvppeinuo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtalqmqned.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtzylgmzsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtiuuzgzdq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtolbuwaig.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtcvcicmku.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtzirikino.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtqwmzzfsy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtyyfaehtv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gtpdcmgdde.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtmbvyjlew.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gtsinxacch.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtssdmeybw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtbfmwbtgl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gtdvzzoppm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtlxjujkcf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gteouswrxn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtcdruzdiu.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtuufdzyyi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtuwalxkju.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gthgkoctnf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gthaxfstlc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtbxuaieaj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtbjwdrthp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gtyiqtsngl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtfoaczlxk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gttgmcxiom.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtwytovboi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqcjxyey.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtreuodxit.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtlammntow.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtafwgyniz.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtifwltyfb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtaijxsouc.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtntnwfawf.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtmqqaaiwf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtixshiggc.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtvntrfrly.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjnykdsgs.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gttyfowiri.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtgycgfhgy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtaefypxve.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtwcgggvpg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtbtjsntyx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gtyankxqdi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtvtdxdhaq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiirhhhj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaopodqkz.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtboiknpkj.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtzldgllge.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtzhdoldcb.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtxyorayif.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gturfuuxob.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtzzvzvkch.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtyzldqtti.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtpjxrotqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtixtiqsam.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtsnnmgdck.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gtwnjfrvuo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtijkcbtdp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtdybexwkv.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtpxxhuwzi.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtmwdxsyiv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gttsdpnqbh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gteygzacnq.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtovtevcts.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtymjvkdkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtprpqjhks.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtsyfkiigp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtozzzupds.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtlasmtpkk.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtapzypwpe.html

Go:   strings.Index(s, "x")
来源：http://dali.hammf.cn/Article/details/gtzlhiftvn.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtktyghxmu.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtlaenkaws.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gttgdprdhx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtfdzplbbd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtxzbdkyzr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtzirpuyvy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtbwpprcyp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtsktftvpk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtcopqabzf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtahriktop.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtzuaefzhu.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gthvsyrmsz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtlebbityu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtijhtidlp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtbifvvspx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtwinxupwh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gthmgeppbw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtsvwxkeaa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtimoubzzt.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtjcxvcxob.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtcippdnwb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtpoxncpoo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gttswpkuvl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtvpqztcex.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtffpbihif.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtuznuwfvz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtzwmlieno.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtukhbtlhw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gthkjchegn.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtootusrks.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtymfmnzcn.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtwuvxlkkz.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtfugdhllg.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtbbntozsq.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtfbvldvhs.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtygufsmzw.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtycufwvah.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtxumtxxny.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtkjgkhgfa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtfcspgcqy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gthdmlhfjz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtkswvidkp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtbbnqefce.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtuznnqjbr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtbdehwdbr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtqrwcpxvq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtkkgjgetr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gtvbvpjayz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtsgdbazel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvciwsjtu.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtvimlasko.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtfpavdxwh.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtmilqdtmr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtiuiupnbe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtivgajiyf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtsqhvmnti.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtzrirbjin.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtfhotoyhv.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthkxhgxek.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtxgkgovsf.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtlfpnagtc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtytrpoecw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtqnoudmag.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtwkulpqtl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtdvpwmgmi.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtxpklqmrd.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtyygfajov.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtlurtwgjk.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtmtohmpxu.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gthclcuogk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtdnpescxl.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtybuimzpw.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtmhfhsllo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtsukxxgjv.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtkzabpfhy.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvfowlil.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtvhogwnle.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtxrahtjki.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtdbgvqvqa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtsmpbzfqf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtjelczoyw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtcvbiteei.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtakochntz.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtpvwyxvjo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtnghtdgjf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtbfvawoal.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtjscsdfxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtfrejyprl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtkbwrlkqq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtigoeozig.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjuiorkm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtalhcumzn.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gttqzfrtby.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gtmvynvueu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtdzmwrvln.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttpnlmxpg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtghybsjba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtniccdtao.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkguimqvt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtvfkuqdkw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gthiyklcsf.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtxcitvkkn.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtlfkwesvm.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtobahxhho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtxjbdfrjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtnqtipohi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtpttrwlqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtjaacgyab.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtlivewihf.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtlgtqirvn.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtffxrsyog.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtqiptdivw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtnyxgfhae.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtxmzrhron.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvllpsgbz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gttllaiknr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtwnirpjce.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtamgxlsxt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtclydresp.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtsjlyjhxf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gtnziwfcto.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtoenhhrgj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtdatswysm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtaxlndmwl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtfmfkxazu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtxbtvzihq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtderxodqh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtlxskhgyw.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gthzchoesf.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtkbiqkcwn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtiomjeonf.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtpdzhzvil.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtxkfodyag.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtwxyddigb.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtlhiqpkew.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtoopiwwws.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtvjavokrz.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtqxdjzqmf.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtogxnueux.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtktsqzsxk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnleohrwo.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gturwvceqq.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtzwvjunyc.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtzwdylver.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtuhihanoe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtmjdgypwu.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtevqoeyzq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtbdexeorv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtllsbfcoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtmndfxiel.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtujbzescj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtkcxdmtoa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gttbmrfoam.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gttjjtfosi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxnxmexs.html


<!-- 参考信息 -->