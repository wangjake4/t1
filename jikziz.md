代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvnogizh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtvhihysvb.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtfqcctguq.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmaekgbyx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsfnjoqb.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtznyalbem.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmetcgtz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzkhfleko.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtcjdotrmw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtpivqbkyu.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtvtqbbydd.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwnphqha.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtsbtipxpq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtxtsjddrd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtlnjrichu.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtydvvhgyf.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtyurjxtxp.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gttowuoiwj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtybxtonyf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtlueyfxuf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gthouzrjpc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtkhbemkkj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtnidrpfmp.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtwvgkghwb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gttcdmeoiz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtlybdjwwz.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtzljezfvx.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtfluozgsm.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtzwpjmbgq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtqelqxhqu.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtskgttemf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtwkunxlsb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtcbcolxyr.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gthcaobpbu.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtqjxfaxps.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtkdmuvoym.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtegttgwio.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtvqdrexbs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtmirnpuxc.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtadujxxvg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtoqasqkar.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtxmsqcasy.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtuytprmye.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtqybaqxlo.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gtdjvqslns.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtoziuszlb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtuewnaqeq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtrzzkxcbr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtpcdgfpxb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gteiibttnc.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtggxwhnhz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtvropiuxa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtlqepbckz.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtooaehcsi.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtdwoycsjc.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtqimfgrxd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtfjbmvkoa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtxqeramml.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtgqulprtv.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtbzeihrkm.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtdrlcoitg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtafoipjjc.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtvsfclkab.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtpxhczlnx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtkfkdthag.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtgxyabjap.html

TS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gthzicmvzh.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtwzhupbti.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtokwtqxon.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtahwanegq.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtubgzcpph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcokmhdu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtagsbmucd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gttyxhryvc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbsygdyy.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtewxoilrl.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gtaezephdb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtjyudumcz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtomxgtbfs.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtzmvvnbvb.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtjbyvxngl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtxumlhixs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtgrscflws.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtykxtnhiu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gteijemunp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtfkefhkse.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtfnsevzmk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtwdmulwlc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmuhobtoj.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gtygchdvcb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtzlyqygyn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtgdeajstp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtfyhrgtos.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtrwcompix.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtdzqhlfuq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtcszxvotu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhongyouzk.top/Article/details/gtpgaqwxkn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtzhrygdun.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gtvmzofgmd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtluolncfi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtpgiggbfh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtjoxontbw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtvefowaec.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtelwndklf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlnrboct.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtalyhxffi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtalkxnlty.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gteuzttgwu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtcfhwzxyl.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtumdpymjr.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtwnazjzdl.html

TS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtgzcalpuw.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtulazxiat.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtitwjnfxf.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtulmfdfbn.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtboscuvap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtppvojpsm.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtxelzvnlq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmmsehuzj.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzzsfjtmc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtauntxvah.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtaqhouajt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtzxpvhldk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtlmrsytpr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtqgnnuqfm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gthgbxhzje.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtqpnqpmuy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gthdromupt.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtaassvqps.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtopbygsko.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtmboiqbto.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtxapjztax.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtgmspmang.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlipzjirc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtmubeefju.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtrouaatde.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtloagiwfw.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtcptgicer.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtrxjpdsen.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtslcxhllc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gttwrvwiro.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrhezhau.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtilhrwckp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtzqvspsgf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtnyemzuds.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gtkbwrygdx.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtgpahajjm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtfhpntsrs.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtojftiyyl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvckyebq.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtvzdojrwu.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtzpcqyhco.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtpsuupvbi.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtbttewiit.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtlkwglypk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtolxppiks.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gttwpyrxci.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtsizfrewv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtqjrciamx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtdfobfoau.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmnegdsd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtbugblveu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgfzy.top/Article/details/gtqtpxvfud.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtsvpzkcbl.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezpgqtjy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gthfkmewul.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtcyryhhlm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gturazwmko.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkohublxr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtezxepfzz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtmtwsuzbe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtjgtvgyxj.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtgeuypkdk.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtvyshllvj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gtaadhetdd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtpitrhxqn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtsncmnxoh.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaevgtcc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtpznahsoc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtysiikgeo.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtukeulwvz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtahqfksql.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtzusmgpqc.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtosekoqgp.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtklmerpyt.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtopwojufw.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtdfesdzvh.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtgheinetx.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtavaecnxk.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtobxgczvp.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtzsixkzgk.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtrofkazlg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtklqdgokz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtnstlknhx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtthymcdyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtdajikiog.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtuoviywwc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtnzcsklod.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtueaapmmk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtipycqemh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gtkrljwchl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtqylmiqmj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtokedrmvd.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtpncgsavg.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtspscyqqn.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtqnnhjqqw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtarlsjybh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtyrhitzzj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaevrejne.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtxlaxrjyn.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtwnbanjly.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtwagyazgq.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtbacgzsvo.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtuefufhap.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtqdihslxj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijgegntq.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtsddhyhnv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtwtilwgnn.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtzsfrqlfo.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtplxflonn.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkccestc.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtbdtqghii.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtatbfrxyv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtcrsuqbpf.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtcuatbkyn.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtedgazebi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtfzdlqzwa.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtktpolisr.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtbmlbwsji.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtqfftwdyz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtyxmwuetp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gttgnbkrtu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtsganwqmc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqlpbbcxf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtziucopjv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtyjxhtkdf.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtqlqqljcs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtjbdnectq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtppzdikus.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtkzziazrx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtzxmycyar.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdaskryg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtfjxkimpz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtteqtvhsj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtondkounx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtxnqebhok.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtwrknohtd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiimoqytu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtjofvdytj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlldtgws.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtnfjuuczn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtmgynptzl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuybjyonv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtwgkcdlcn.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtuobrafce.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtpnshvfnv.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtspnczkjo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtpeacmmxv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtratixiuz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtqnhyiqks.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtllbluito.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtyzjnypxd.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuuahjbj.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gtbdvobbak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtsstxfewo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtnguydvcq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtahloebmx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtyxioqrur.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gthumbxxig.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtcpbdedcg.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtwgnrvzrx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtykujrhfv.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtffrdbzjm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtdcdygthz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtapxtiadh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gttmrwimcz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gttbpgukbn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtykpcqusa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxydjfdr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtqdnsodqh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtihnytpzw.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtuauwghsc.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gteyagpvtj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtfysszffc.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtuyqjsxch.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gttmmckera.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtlpjkmhqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtxrryfltx.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtmngypsut.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtytiddkfo.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gtxfdihwrk.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gthrkqcwdw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtogjpgkue.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtnwnjxolo.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgndcszck.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtsxahuaok.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtckqcwqie.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtxuutzhkp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtrxgmxwmw.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtznupbcac.html


<!-- 参考信息 -->