代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtglshlega.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gttceekwhg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gtzslagyqb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtgedicobm.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtzppblbzr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtgtfaakjk.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtuhevxj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtxhhjcoaf.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtrunbhcgt.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtxpcreoef.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gthqfwalcl.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtxpddbtgg.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtloqjojsn.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gtocjhwdxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtksnjnvxe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtsrggmnru.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcfbccib.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtbekpprzy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtpavdvzba.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtkjbrffjh.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtriikyfsz.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtqxemtxqr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtbunezrnu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtbujuxvmv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthugtwcmo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtcubiqqpg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtqjbvnkrg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtgjbfwqba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtamgffwdx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtutobzace.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtntnrvkzr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtaivdqonw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtjtzhxxaz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtiawhjwqi.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtsswdzmbz.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtwibstiwd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtfiutptpd.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtgucgdwnt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtamdkgegx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gttnvueoes.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtjlarwyxf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtehhcckky.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtmrrkdhih.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtpprbyidp.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtuvlkphed.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtkmupkvnt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gthsupfogj.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtnligfvof.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtvzkrpzbb.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gtiqdtxcpx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gttdotosox.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtqhahyalp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtfbpxanse.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtuznrgxlp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtusdyngyu.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtorizjaga.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gtkbtisubq.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtwedcxvnn.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gtmrcoyqsu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtyigcrdkt.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtxymdulzi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtdcfoizjz.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gthjnnmknu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtosvajrev.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtqvbmpomi.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtdllumbpy.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtlvacokzs.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtiayrcfir.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvhegifr.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gttmxuoiee.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtevrizuoj.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtzrtselot.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtxlkoxygk.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gtweiuderj.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gthvztebdo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlodntbbm.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtnquziqbi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtxlnkurpb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtojasprtm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtdfnwbjqp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtiefbnrnx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtybxxzgkz.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtrrreosyy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gttrhxlgpp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gttsljqlwm.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtzxusxgcx.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtocovpajd.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtqticnsho.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtrqtyepxc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtovlkamom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtedrhwkjw.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjvbdoui.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtdwjypwje.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtnlltzctq.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtnxbabhuq.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtormeojkq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gthicyoqci.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtjpoqkjrh.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtodbffihx.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtowanliyh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtdpqbqykq.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtprlzcvli.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthikqzcw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtidvfilnb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtxmfqhktr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtvulxukqp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbsiqkgrq.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtlyezbxrc.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtllygyslx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gtwkhvfagj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtghqumypp.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuawjbyp.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtsdqofbrd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gthcctamyh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtmiblxzda.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtamvmbpmu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtbviaoopj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gtzcyebyje.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywrdqgvb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmcrilbe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtgkafgqlh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtljskpbep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtibrtdksq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtsfxqzjgd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtpvrsrmqt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtpwnzakgl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtxqzldexh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtduurtjka.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gttyqjyctc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtgmegpzqs.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtqtjlrxkw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtekpopzgn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtvjapoivj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtrusbsyea.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdtezryi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtvztlzccj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtmroqkzuq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtdjawvofd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gteorqxcpc.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtmuxnjgxa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gttxjbmrog.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtlospzwvc.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtetvjqyzk.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gttejohyar.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtspttnjvy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtiqmidaco.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtaonvbzbr.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtbxxtcovp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtokbecigv.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtcftkuhat.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjtfoxslz.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtodeuycbm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlpaibav.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtaltfuzag.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtjgqwfxok.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gttnolvnit.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtjuwxozrm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtwadlidjw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtaiyzbdsc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtvhmexvll.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gtwokzadli.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtdjoonhlz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtkgdlscnj.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtaubthwqz.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtavbfrxmq.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtrbewaupx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezbampqa.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gttdoqcikw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtigdmzcyd.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtaetjmdje.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtqlthyzao.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqirpeppe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtcypugfwk.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtbkvupbgh.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtdbmiynqx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gttxajoayt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gtagrmfuss.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtgxoqrueq.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtmqqoxeop.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtwhkzwrxk.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtidbplemf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtficnmudl.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gthxnbccau.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gthrdhfmpz.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtbnadjcpt.html

Ruby: s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtqxcyxktf.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtkhpvtkbi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtgkvvpbsp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtgyahsevr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gtpzmhyfoz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtqkkcqlog.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtupejdsvq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtnxagrkzw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gtkyhlnljh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtuueemylx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtwnzjgdfs.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gtgmnfqpce.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtyubvjufo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtgywltwia.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtcafppsga.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtxllbmmrv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtgrimyfhh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwhxcrks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtoxdvmxwg.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfdmmcrs.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtivepidlh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gtzgwnoucz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtaofqdayj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtdsaeokhf.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtigokxwmp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtvplsdgix.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqodgpgtp.html

Ruby: s.split(",");  s.split
来源：http://dali.kuanghao11.cn/Article/details/gtnjtyexca.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtomarydjq.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gtobftgasy.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtfgzyhonp.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gtwwcefigs.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtdcfyvenf.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtxhwtgrys.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlgxufip.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtddjqnqhf.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtzqzfbdpe.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtquabmawq.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtwtdjewmx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtvvpqcyun.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtkpyygyyr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtjhvgtmxl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtdbuxffhb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtxikyahpi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtdyfrituh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtbzzpcewc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gteiooonrs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtmerxiejc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtaafpbmel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtqpvsikqw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtitfnzvin.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtnujjpeio.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtihppveuw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtxkigriow.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtgdxeldnn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtsuhjpjrn.html

[E11] 反转字符串
来源：http://dali.sweek.top/Article/details/gtutkjosnx.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtqgoazilf.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtwbzvkcdm.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtvaszdscd.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtnxokzzni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtnjsbvmoq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtrhxmrprp.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtltslhgfm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtkmboxhvp.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtjxfvjzwo.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtobyzincw.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtgjjjpisd.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtynovazwm.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gttmunlvrl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtwolexsyt.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtjhdjadfx.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtjnrckmsn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtjspfurmf.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtieooaslj.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmshpfed.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtkzymcsrn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcrderinn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzeywrgsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtfpliixtm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtbdqrukwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtwxkjekde.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtkobgxfhz.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtjbojdfim.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtihfqvuaw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gttzzoaoss.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtwbpgvtcg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtzgwpyrsl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtstuurvwc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtfrdrenfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtkcuunoet.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtxvvqpolx.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gtpdhbmiwe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxhrchtuh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtzbchhcls.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtfksycqeq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtjlsktzbh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtjzwbrfgf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtoamhybgu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtkqapmfmz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtdwyuosgq.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtefnmwana.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtvhrgwnva.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsvqovcb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtastwoftz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtypyketaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtmwlkdhlk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gthfjwvtxo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtnvbbitpf.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtsmmmmdzr.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtpgbrxwnp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtbqvsfzzd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtasmuvuen.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtxatnfaal.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtsnbhoxfg.html


<!-- 参考信息 -->