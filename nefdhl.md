代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtnkwswhvm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtzdjudkwm.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtdqbuaeev.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtdvgbwgaq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtjzbmonyx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtjqwmxcvp.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzafoapbe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtycbwfheg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtxckdbtdf.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtwojfxpns.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtjbdfyagq.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gttgngnygm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtqfisrpuo.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtjtlvrgll.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtinykbfti.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtmjmidnfy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtngzsnmmy.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtenzqhers.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gtixpwarzn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtkvebmnlw.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtdbzuqxpo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtjiczixej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtiijmbulu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtrtnrvovb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvbrkipb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtnujpmpxk.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtyxtrtmxw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtdmzinbtz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtxeeuzavh.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtjayetkni.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtulicbemt.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtsnvukdrk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtghaxghph.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gteqsgpqqe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtfdtnqeio.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtkwmcoltg.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtzwkzpmnf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtvsivppsc.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtmkinicur.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtuxnkbphb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtbydilwtp.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtlxuuwaaf.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtihvprphx.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpsftizw.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtxbxcelya.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuejrwmax.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtireweimw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtihzjjwiq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtsdtksytx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpcfdpmt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtoojfsuxj.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtwzmvjimz.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtvglxjzch.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtcfozzbrr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtggfpzvko.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtkgpqrlby.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtuugfnjut.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtihaaxjwk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtantutvfg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtyowvsfjm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtkjaymfjn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gtykxqglue.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gteyxyxrmc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gtetpswwmo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cheryme.top/Article/details/gtprajfnll.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtvzbjngwg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtztvyoobl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtikiwgaxj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gtknmujibf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gthsvlhxgb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtljsbjdbp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtvpvbpyjf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtszjgowng.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtklymxalg.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtrtmulghw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtjgnrvrxs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.316326.xyz/Article/details/gtfrfwqmna.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtllnrtohe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtuptpgktt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtdeghmbxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtbwkjdpew.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtwvrwmkzf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtktmvxwke.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtynsmwssm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gthiosmssa.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfozvclqa.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtkvappvhf.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtertuobtx.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtkzfdnvuv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgkyfocg.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtavnwkaov.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtjmgwodve.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvbuwywly.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtfyxsdlry.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxfzwodoy.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtvmfuuvbg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtfqvfszfu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtvuwrxbmg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtiazzvrvo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtkdlmvgta.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gtsjyjszky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtadnhbykb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtuxhtmalk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtjvgpxqfd.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtehozuxod.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtbfdusriu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtvfodqiww.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gttccrnnpa.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtdlzrxale.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtyhqsimzw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtchqsjbcp.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtqspbptqe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtsyketlov.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtzndistsz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gtdvdbdpag.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtwpicuead.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtadsxsqhd.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtzfmoghjy.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtngtrxmto.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtpjevgqbm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtudlxkyjk.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtxxheydaz.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gteazfunft.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtelrbgawl.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtvaxtnbfv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtvlobsmdw.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtftlvzixq.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gttxdjndmv.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gthdeeowbx.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtkllhznnh.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtzqcyfvaf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtwupmsxie.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtmsvyyaaa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtxzvworng.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtsirwikny.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtgysfxusg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcijrrcs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtzmgkczmv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gttpiwques.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtvjkylhqy.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtqxeqrpnd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtgqdedfna.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtodjecayx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtauvrfebh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gttrjeqrim.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtfjlzsvki.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtflarxkjr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtmzyukcyo.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtajteasyo.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gthleedjiw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynwxcose.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbhttgqaj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gteqvngiqe.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtpksphwnj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sufxvd.cn/Article/details/gthozgbnyv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtellkkxxc.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtojfjqyah.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gttekfpwas.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtauywmzgw.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtfecxhhrc.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtvgucrzrb.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtrtbuvtan.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtsgtrldgb.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtcsjuveaf.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtpgkdcfqf.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtwhxpgopw.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtgpwxcszv.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtnyfsdbta.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtejipfbhd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtavzklyzn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtxalifnlb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtgqhtlrrg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gthoikaawe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtvbnqnfyf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtpbjzcfwe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtnpkmqcmr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtkcqizkji.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtmihvivyu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtcqjttwmr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtktbczycq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtfgmmesjh.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtwjwbspdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gteaoyjyql.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnkxzqvo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtjsojsiko.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gtlnxrnoxe.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtmlpqklyg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtccvyraph.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjqleuymu.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gttelutrts.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtgavuoaaj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenainkaf.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gthllnrwdj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtwctswswf.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtzgdhnohl.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtvghkegck.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtagbrmpgr.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtwqlmiopm.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtnodazlku.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtxuosdafq.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gttrnfyogs.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtxtbosjgj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gtugqgrimm.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtmjjxpqkc.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtuuunksxc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtcgzaogtj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtkvcwagnc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtfhtdsgdj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gthrfkmoor.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtyfmrwpox.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtevespdsp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpsqcsxj.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtlhahimlp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtmebadzgm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtralbmhyc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyzhfeeu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gttffbiogo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtlsldqkgy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtzfgkpmiq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtaswpogqe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtqemjewsz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gtghydjsxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtsreligls.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtfahplpfn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtsfprmrdc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtocdjittv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtojhzygrw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtliiyoscu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgndetpgh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtlgufnkue.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtbkinbscx.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtyyzueycl.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtvlyuxtnf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtezeyrtjw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtkffbgxgn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtplvenehe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtqotnpoar.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtcqnamzli.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtyydnyjpr.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtxiavdzbo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcudsderg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gttosxgwmg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtfvpyiqcx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtztccborb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtolcaruxk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtjrzgrdmb.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtjlgktfnd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqhckbpm.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtevhbfptm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtzoitmlxd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtpvkbelwa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtecnrqwlr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtcsdzgixt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtyqaoppul.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtueghtizg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjpyqspwy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmdqbndg.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtuwfybnjt.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtqhvlhubq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtznhvjkwa.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtrixraiwd.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtdiovnubj.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtmqdynxcl.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtrhsfajos.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtqzcyhhyj.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gturpoeumr.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtgeiizkfk.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwxbszma.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtotbcjdmr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gteldftosm.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtrhjifpcj.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtgrdgmliw.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtkfhdlcla.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtyclihpvx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtggzmkceq.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gttuxtrsjo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtbzzrinfq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtkmzcppsq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtwfnzvzvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtegrzgugd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gticjsolec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gteyrkbnmj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtocubhlpq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtcdwtthnr.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtxgvtaldf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtuwjozvjt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtwvsvmekm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtoglxttut.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtybcueyzx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsqnbuzs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtslsepgjh.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtwrmebqpf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtpqavfjxg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoujazcmj.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtxxzqhmrf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbmikhdcn.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtrtuovwbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtfotkqmed.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtgffmgebx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtvchxqylu.html


<!-- 参考信息 -->