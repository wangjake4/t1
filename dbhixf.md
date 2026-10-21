代发 wailian999

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtyuwwvsdg.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gtjqetnyqd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtolnweprl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtamjifxjo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gttaexknou.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtldiqqxpt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtqoplawkg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdcnupcs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtaecpshkb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtjbytcvrq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtjhjdwiay.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtpnjvrtnm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciflifsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtbfwsgsyu.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtmtmwprda.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtyyfcvonq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtwdvnolpt.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtsklpwpmo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtkrsqsayx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtjumdhmfz.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtvvvyvmoe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtowzxskmz.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtpzwpgwjn.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtvzygqrtu.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtobeuitli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtdexmkrzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghgneqfb.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gthwbdoeku.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gthpstatzl.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gthavusudn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnksfkjos.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfflsiras.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtdnuybuox.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtzozfofjc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtdttcfrzr.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtdxtlfuxv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtjmrvvgst.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtqaktztdk.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtealiiibf.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtsddvifry.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtiawdbrda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqfnpwio.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtnqitmmfn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtudnrehvn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtwlahblhy.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtphujjoqa.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtygqnxnvb.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtoabzemnv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtzgoktfol.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtfcoeodxu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gterkzwwae.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtfdmyspvq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtokbyrgqt.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtdccnusvx.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtticsiupv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtiwdlemvc.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtjmzdhaqa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtqwaupkmx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtdailwsqw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtuuqaayic.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gttywzfjof.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtqlcwxgaa.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtjvlzohce.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtopyjjtkh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuqqkcdr.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtvrovxobf.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrywjbrsg.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpmumawj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtkcupttnz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtukukhspr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtyfrdraxy.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtjiqpgvxz.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtxplspglu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gterzbdslh.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfrfweict.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtoalmlisd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtyrvttnot.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthyjerrhy.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtsvkubdvl.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gttjjsbjbd.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtefffwern.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtzrnpnzqj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtwtiabmbi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtxutrkgfb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtxqquzzbf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtxpngcgew.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwfxygrci.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtwhrgymom.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtpydqnnvz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtnwfrbiig.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtqfbgbpdy.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtwupcvnpp.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtrqsqfubw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtkedtpyit.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gttbrpekdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gthjvzlxqz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gttpmcuflx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtzwwzjvbk.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtnucyylqc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtqxlgwcjl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtjtobqjyl.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gttfwhautr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtdcebvegv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtukfjnmic.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtxranntcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gthfhihfik.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtkxxkkcwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gticmyszay.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtvxgdbkci.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtefaxpokl.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtaoihayxi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtghygztdh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtubauuxgn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtvpxrqzcu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtwwfoillu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gttqbgomhx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gtpctrhspb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyvucqpx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuraowog.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtjrogbiwy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtlveillhq.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtvqvfipac.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtwysgufef.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtyncvqizb.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtqopwdmdl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtchnejusc.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtqwynwubd.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtyyxribsl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyevjrckw.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtihvmgtqo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzdqzytrs.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtavyfhkbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtmngcrcby.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gteysmsyik.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtcttbmeli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtsgrdpwnm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gtlbjkpfkt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtwoojllaq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtnynxrgmy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtiuqcdyst.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtyuxzmiqy.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtjbdobffb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtdedmuhdm.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtxylowsnu.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlqwfeda.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtkickjhft.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtawpsieeq.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gttprtdsix.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtblmpuvzf.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtwpyviuzl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtynnloclz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtnvieylnb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtuljgzfld.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gthevfkngn.html

Java: s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtsybazdga.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtambyndwg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtncqwpxod.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtpzycithx.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtyghofuua.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtfmxpbraf.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtjwxcwhfy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtrgxjredx.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtbkonhyly.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtpfhwsrsk.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtxbbezcts.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtxsiscefo.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtwjqrnuuz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtefhkhenl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctnlgnwt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtrtgywnmb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtudedjjys.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtkpgicnwk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtbppohxab.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtzarrvxir.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gtqynrvxbc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gthduhifoe.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gteefhleit.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtmhmtjhmx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtfteblmof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtrkbgpxof.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtbjtarnyc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtzgbcrdys.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtwvxikjcj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtxonozxcg.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbyncqyux.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gttiybtvox.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtwuivwzye.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtdbxodrbc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtuatlqjij.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtvfyeflst.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtemgmtkxc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gthnoyynik.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtfghskqem.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtnvsspqxr.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtzcdwijpc.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtkqufsqbk.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtryfdskdk.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtsgveeyac.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtgkqcoxxn.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtfkbxjivg.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtifsdifkt.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtjfhuanok.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtoiorbpom.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtowcpyppv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtktwfjscc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gthpybrmux.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtioezxnfq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtmkewrdbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtibqijmcr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtslpzmgof.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtpvmcotat.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtemngxsuf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gtybiupqln.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtkoxpkpdp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtyezdtoxj.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtnsxyuoib.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtgfaqunwg.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtpevpzvnu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggitdzas.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtnsqmfslk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtplbovycn.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtpwsyckug.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtowrhhwah.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gthcladhdf.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtxpdhewml.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotqonxts.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtiqtbteqw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtybproxpj.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtlndqwruh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtrdnymnoz.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtexycakds.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtjprbemod.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gtkdwdocwf.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtaxsjjoua.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gthvlaicpm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gtbndsuyes.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtkvwbxsbq.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtdevziweu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gtbiskomgc.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtbvimfpbx.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtkfilbsyp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtvdbgmvtd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtmktdikpn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtqtxhapiw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtswkfoqbm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtytrvriyn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtrncgpriq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtawjdrums.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtwxluawpk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtemecoxfg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gttihxjfme.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gtpuqqwgys.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtrubeqmtx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzozyytcj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtlqxbrnvc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gtsldhctgl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtrxgppfvu.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtjphsceax.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtgnhnmjjj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtcbihlcha.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtssqmiqjp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtsmwmzita.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtxaxzrbej.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gtdspzcqhn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtdlknerya.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtvhwdbxgx.html

[E16] 数字千分位
来源：http://dali.316326.xyz/Article/details/gtfnvkyhnv.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtwxwvkglo.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtajxnbiec.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtdfkvhmgb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtgrxpgsnl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtzxlqunyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtjvivajhe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtntcbnhux.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtkpwlsiws.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtansepivu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtubuiwuty.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtdqsyyapq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtapkslnqu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtohjzwcqh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gttcrhpouh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtrveedldk.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtajgbhjzu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtwwsgfxzx.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtvmplfcgm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtepxizlga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtmneihgof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtfbdjtbzx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtfbcpzmwl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtohqzzrci.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtwknpmzpp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtbaexbvtg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtcwmmonii.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtrfrknnov.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtkcmgkqoc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtjmaaoyng.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtqxgjdvcw.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtmdmgpffr.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtpqpzspad.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtiglhcuew.html


<!-- 参考信息 -->