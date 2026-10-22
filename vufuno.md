代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqpjofit.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtwwugoggx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtalvagbna.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtzhtwymuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtsfazsxtr.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtsniijzzp.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtatcnyzsv.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtxszcgkly.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtpvvbjlkq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtjebfihyz.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtubhmtawh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gthvhuilvx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtenhycumu.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtykaggpoo.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtefoqcggn.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtgfbuzllc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtvbnawkzl.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkmmarsb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwgatwfn.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtttvcqehj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtegigffxx.html

Go:   // 手写双层循环
来源：http://dali.yj20258888.top/Article/details/gtfljcbbit.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtrkcgclcb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtyazbkpud.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtshxkgxgd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtptrxqotp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtxzwjatyh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtggxbklwf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtaxlpgcki.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgzgnexf.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtpbmizsyh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtdpqruetq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gthwgmfgtw.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gttxtanaco.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlndbnubu.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsltgdszo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgktxhnbs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtnbwxscrj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtjfvfahmg.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtrwlbrraj.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtmpgzoenj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtgxcrphxx.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtsirlhhqn.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtfzahpfrl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtrpthyqiw.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtiymjfqta.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtbxikgtoz.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gthzyqtthw.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtmqcfwfow.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtzhhbyxib.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtebrizcym.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gthdnjnpgj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtpscmvwfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtievbmkqi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtnpkstkbu.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtacoyutij.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtgxdqszuq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtzvlmmxfq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtbqarqmho.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtmfsilyyv.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtxwswcvwm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtevuchtxb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtyiwoqlqf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gteggaekru.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtsddgxqbp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtpynobhck.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtycsprazc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtkqjclgjl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtxrydiuul.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtdvmexniq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtvcwqfhun.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtwagiqjla.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtipxdrk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtlavsvggy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtrzyyamly.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtjvfgslge.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtjqkrdanq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtfwtvvyfh.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtnjvwigjr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtghcfmfil.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtadudiucj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtktggdcjo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gtfiyvwmuf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtzcxpcedz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtvepugbxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtqskwlinp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtnkuwlhbv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnwliigor.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtsvagbfbf.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtprsdnudx.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtxfdxrjqp.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtkbztjdsw.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtbvrqbwxj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtxaimpzxu.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gthpduplvw.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtyvprssgm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtojmppwht.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtsyircunq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqxdgeseo.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtvmaatzlt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtxocvsagw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gtlolnkouj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdvuebci.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtrdodghyx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtetbnghfa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtvrpqibbh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtujqkzfki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtwwjbtpkz.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtofieboqu.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtwcdzhtjo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtfjudmkpx.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtbethzjma.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtffnfkkns.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtpsieasqs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtpzahvoyw.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtjgcfimey.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtcumjhilh.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gtndjriveu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtiixopjzm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gteakigpcz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtijuqpfzp.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtbojgvqwd.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfpzcffu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtdorkttrk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtetwmglzq.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtrgbnizlw.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtimzjjnhi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtgajjsxet.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtfiiblxet.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtkyxsmdfu.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtgpdiihdk.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtxqnbkigu.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtusrlsina.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gthhchfemq.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtagqhhxmk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtutpctoia.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtvuqzvmrx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtztzcvbzy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtmitwkhhw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtciacxhyu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtwmgokzxb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtagxgbrlp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtehmlsbnl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtacnmeocg.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtxuwapqxg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtomjevlub.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtarlzdhxi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtlcxjoovn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtpihwpnjz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gttnmrudbn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtyhqtwgiy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtdxwhdnvm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gttvzvpnkb.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtzriazhvv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtnmmofpkm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtgmuqnewf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gtcmzvirpe.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtkxyqrtcq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gtckdntikl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtolypnyxp.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtmwrynvgy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtpegjpsjj.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjtywxar.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gtknynatia.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtxzqfxjtk.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtiaamwyyu.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtxmcwwkcv.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtovthltxn.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtstaqblwz.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtgjkdtngy.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbdayhvw.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gttwvugpmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtqanijsya.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtoabhiyup.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtluzsvwnw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtcqeovuvk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtchdzitbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gttotbsrcr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtgsvwlmvk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtfpwzagbo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtnsxhjodh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gttzctlvvw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtpmdnemnx.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtazwxhgqt.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwlqawou.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtccroszox.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtesdxctjj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtypwqyunp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtgsizaxez.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtxisybdbg.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gthwykgtsg.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtglpgmujr.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtfzhperxw.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtgwmjqctm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtayntcvsa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtnydxinrf.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtjektwzmg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtnemxgnbn.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gttquetavu.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtjpbqdrsg.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtkavcoxjd.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtzmgkyzfh.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtaczkrrpd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhmsyoav.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtmnxinxiz.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtacljuyue.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gttgxloqrw.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtblmaovdd.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtbuhbrsfu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtsgyjcjtm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtolvgxuel.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzqxsqvm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtwltfrihf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtlixawncu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtxolfxvif.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtdefgaofm.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtnrtfvwcz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtlfynvyhe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtkwmuhsjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtpbcqtuxj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtkveaduiy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtpezpkcyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtnqokjvfz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtngqensfj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtertntzti.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtysfdjmcp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdezltpg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtmyhijnom.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtuplbcfhx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gthyfhuhrz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtnxbyfjon.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjpxdhae.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtntcmecaf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxvwctumm.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gteiktzgxj.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtkdyqaqnn.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtqdxuyden.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtetrcmslc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtiukpipui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtmdmnledn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtunerogjg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtpyfgdfdn.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtceorriyh.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtniyfngwu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtzkgypnfg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtetlispuc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkspsndsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutzzarix.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gtxgkuxrhs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtdcjmmudf.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmagxmhik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtowfrgzzu.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtbmqcjgqj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdglbzaru.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtmeapiwuf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtpuksfcfn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gttdcovkrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gteqzpbpkf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtvtlnnpcf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtwipomyzx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtpmuqbhzp.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtcgffjmhv.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtdbkilame.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gttewpyzgz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtlxxmrfxf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtdkqqjfsr.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssqyhzhi.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldiwdiyq.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtgngresfq.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gthjaozlcg.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtqcfsqvxn.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtswaaezvd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtblnoryxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtqtcvrjfd.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtjnoxhbph.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtuxovtkpm.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtlpjdvniq.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtglolunxt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyppijcyj.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtvbjcknoe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtnfanfufk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtvijhaerq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gturfjtrnv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtlzzeoeyy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgbboqyu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gtjfaupowr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtnzftirsz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtjjyfwxrc.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtvqkrrfzm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtkowljvmd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtoimmepte.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtnuqjxefz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtklqqugqv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gttvdpfche.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtjcwurpmc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtclsffnhz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjmspbpq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtytsxvowg.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gttlskwbss.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgidhjrge.html


<!-- 参考信息 -->