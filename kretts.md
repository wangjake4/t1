代发 wailian999

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtiryeexuo.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzcmplov.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gttfsexxok.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtmsscqfqd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtmpurzemc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtskbizdsc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqcxndcg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtgkpojhdl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtyazxqwjz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtbqoelqce.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtnzjasgxv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtkqxvzout.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtqrfuzizw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtwhrtciyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtjjltjexy.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtyurinscy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtihzukvhk.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtslsqmutn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gthupfsbti.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtkbhdhpdq.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtvufcdqah.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtojlynxfd.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtfrhbluyq.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtabixduja.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtryzvlxfr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtgfofmnnn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtnhqxybfe.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtkjgznukb.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtnfjcoget.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtbfufggpl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtctrasfvf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtdafwraub.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtjdagliww.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtutzlqoso.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtpqrpykxr.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtpzqxpujy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtelkxyprl.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gttgjgljqe.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gtdeatznrd.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtqpllylfg.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtnkifzkkc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtwsenbfbn.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gttvvbosqp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtuwawhbif.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwnzglrsn.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtyjwsnayd.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtrkwafxmv.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gtlgukivqm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gttvbaqqyb.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtsscmupaw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtyzhzsyvu.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtwszsoruk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtsmdcbjdb.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjvpwblqf.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtvwuxzmhd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtokhlzrhm.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtzmddnrgf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtyqchcmkm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtwovxsjin.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gttwhxjcqr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgywzrqz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtfajxgixq.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtaoadxkia.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtlwnaksja.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtyqnqockw.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigfzbtpv.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtplgntgpu.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtkzmrmeqp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtymjnfpmz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtqmifzwsk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtbcfinlti.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtfgosffin.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gtaaejhkpk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gteoyknoiv.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtzgpwxawo.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtpycrisah.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtmaivzoos.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtkwdsnddp.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrwmmnbse.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtslxhnksn.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtlwzvpcjg.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdsokhpco.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtubqgbhls.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtgabvhvza.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtayceqmyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtrusfrgxk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gtragdkays.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtvbyhemqw.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtcrwcrnuw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtzeaoatwh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtfdsofhqn.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqemmdlvz.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gttfkjjqnl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gtjkbcsxaf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtnkmtiizu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtkwcqfkkq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtphdiadoi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtfzhabyuy.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtuskxrsdx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtrimtmpbt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtspipsprr.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtpcvvsook.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtyuejgtou.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtuwbinaqp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtwbezapbb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtvorrylsf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtmqfefxdr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtkmsqvmfx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtzhactame.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtvdipruxk.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtqhwyrbyb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtrtvnudvj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtemhnwoeg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtcpzdoaif.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtfohxwqjb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtmrrleggo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gtcnfjevzb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtajtwuytp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtsmiutetc.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtkpdvkoqp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gthiiijuhd.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtahvjqwml.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtzhxanhfv.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtaotoxzkp.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiwtnksy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtleqmaxuw.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gthbbpqywp.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtxbnycooj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgscvrbrr.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtwuoteyip.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthcisjcju.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gtahlfsrpa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtcxlerisp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtckfydxyq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtdvdsxbof.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtefodjmto.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsshxmsy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtpadarvhu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrycmkfx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtyghlxcjy.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtryhbuzfk.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtjbtgncuz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppcvppkh.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtcaqeomwv.html

TS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtctyiblqr.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtzyjdusqp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtkktiawlh.html

Ruby: "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtjndqrxvl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtlccfprhi.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtudhsobkn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gttsmqbhwc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtmoajffpn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtfabfymno.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtykazfgvs.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtbfmgpuft.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtfyelkgte.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gttrnrpgfk.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtvojelcub.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtlnbybxee.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtakyuebdm.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtmgizttja.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtqgptzaxg.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtooxwfqkt.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gthnnlmhlw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtaeiqsyfw.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gteffjjkbm.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtfnqoasbx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gtsovhllqh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtbvpoxfbf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtvzmvzays.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtamlltqrp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtaakqqrlx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtversljla.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtxxbjeckp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtkskohoqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtrkasyyar.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtvxwkhgtz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqscomiw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gtqdwoqbes.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtvbnkreny.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtvamnqrrx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtmloziexl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabnfxqgg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtnvckgyan.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtbrplefbj.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtwfnmuogh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtqsjalpeh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtxixftqgz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtnntutvxz.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtodtcsoez.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gthinhadpf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gthlxlruax.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gttyugnqnk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtyqklvonb.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtcjkgyniw.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtdwedzfdb.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtwupxjwzk.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtfmvmbsua.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtfwnwmyrm.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtysoaszhd.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtrmsxwkep.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeykrshh.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtqgmlvvtc.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtsywhqhze.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtufidkclk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtpbtkqfzp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtccbqtdbb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtvlamemvn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gttohvhgdt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtmtnmhkzp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtoczsaaap.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtbobwfcwp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtcsyxbvhh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtymvlqdjt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtxmilobsi.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtlovaahuq.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtnnicgjae.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtvrdwjqyo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtjqvqqvxr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtersktbzv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtqmwhzjgs.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gthrueikxk.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtdcnxlwvi.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gttlrcuudy.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtrscmklyv.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtfgbjgrol.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtxphqoosw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gttifwoztc.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gtlqnayyex.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtiuoslpjy.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtldzlyrxk.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtyffaxrpv.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtipgjtapk.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtiwnaffur.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gthaxhercz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtrvwkyoib.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtxitujeeo.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtpfhouhio.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtovhxnydo.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtkotkbeuh.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtgpzxnzip.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtlneroxfg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtvvzcxuqn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvbfwvse.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtykarvngq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtihbdwdiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtukgawdms.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtfmlprljp.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtseuuqleh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtbniahcak.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtzudtmctz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtvookyqme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtzdstocqx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtrlqlofpb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtykeikbaf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gthjsfvjrg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtgeorybxf.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtmkpmywon.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtqidaghca.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtzuqvbiuo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtiabjlsao.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtwfewcwrt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtzwhrrscg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtijzpgqbf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtjkfgrpzt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gthdsgwyhm.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtfnnxtmsp.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtklwbvidz.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtqkxxbgzo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtfbgnwanw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtudlhzqmd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtiqjiwiqj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrlnbhcj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtnxwzvyfi.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtdwzllaeo.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtixfjdhlw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gttjpbivvz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtnybcovqy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbdopqopf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gthnrdcqop.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtmhomdoxe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtszuxdwku.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtermequkb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtdxailpft.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtucjmihcm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtwxwaikun.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtnjlluenk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtrrrlkupr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtvwvzhnon.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlftdtzg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtjggnghxh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbkkohmn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gtjsvhbumz.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtvjkipczk.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtotqeroto.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gtbzjuutvp.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtllhjltlk.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtqeagdest.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gttwlajkwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtvwrooeuz.html


<!-- 参考信息 -->