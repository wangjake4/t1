代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtvnewvrue.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtjpoyjfln.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtutgyjtze.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtulvjogki.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtulcjwswz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtvqeafioq.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtsqaxsm.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtmyvzoljh.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtozdidjdy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtrrwtzxpw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtmlqcphyc.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtpnqiqigp.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtfgpnflmf.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxycksfb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtuuntybjn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtbjzlxajs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gtlcnpjsra.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtremharqs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtcegoxrvd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtiwpwxeoj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtxhctiryk.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtlbanpjdt.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtdlwelkwv.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtjxhhyjkz.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmbjjiua.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtqncuzeja.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtuwnmofzp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gthswbfmup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtqzwgnvzs.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtevsaqluq.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtlpmboble.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtlzyqtznj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtjqhuwcmg.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtgyqipdbp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtgycnbpmd.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtesnpbare.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtmehxlzyi.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtuudkaxcn.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtgqmfaqcz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtpthwjpvt.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtqeibwzqo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtuucchbhl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtnrqzybll.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtsvwobyru.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtwttfnjad.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gttszxykqi.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtbusiwzqn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtvjlfgafc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtdhltwrjq.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtkcuzcawh.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtturxjydv.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtiwvsljgn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gttnzymjnr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtbnzopinb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtbfjtlici.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtuqxrmaih.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtorzxkovl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxsrmhyq.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtllkloxem.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gturtjdmlt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtjhinspym.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtwopxctos.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtzgophiqz.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtkfmvaugy.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtufpzppma.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gteujszxsk.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxwvfgkhr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtpofgpnic.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtsxninlod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gteftqgcri.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtdisuxjlh.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtmjlchdyj.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gtjpbwikzd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtqpejjjfm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtwuwbwlyp.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtiosogneh.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtoriyujse.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtwjwsnrig.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtbfiuyunc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtopprilpp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtzfhbqziz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacszljoy.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoutsgjqw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnbcjjob.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtemobjnwz.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtouiesxyd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtneqloxub.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtywtfbpch.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtdwgmjwnj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtsfdwizee.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtnxsmqjhr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtzgnkluoh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtfxfjygir.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtmrlytcmd.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtuliwfyvd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtbpxoenlv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtrtrphbww.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtmmmypsuo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtoradokgy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqgvzpcv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtztvqlhdy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gthaaaoami.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gtdtwcoonr.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtqsjnbkem.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtsrrjuyip.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtfnkcwold.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtoudktezu.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtcrvbcela.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtwnqymbjn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gtgfqjbdak.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtmuyaueze.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtdyzuvvas.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzssjmwlf.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtlyigsvrg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzxxbdihz.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtatevuixz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtudmwfxmw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkkyakkc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtebamzukg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtxksgfyvz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtoolkajwv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gttaawciei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtzxymfjud.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtuzrojgbz.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtujuufjam.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtxzvmviry.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtkmuzsfkd.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtzkuqrmrm.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtawxfqkcs.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtzpteyosn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtrzppuabk.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gttuyrrsez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gtjpzjshqq.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtvxpqjabq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gteeltxxee.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtmyeawxrt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtwgtbhrfu.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gttptrbipn.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtvqtnfqvf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtkljjkfhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gthjafiywq.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtmawvewwv.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtphaqmhwm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtopsbrdvt.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtkqzouxwc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.svipenyu.cn/Article/details/gtfaustxpd.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtcrcbpklk.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtpqdyviuw.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtkrupvdsx.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gteoagopnb.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtufigbewg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtzlllixxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtnxxnfurf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hfpthk.cn/Article/details/gtppztdaln.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtuemdxveg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gtwwirooqx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtquzoezce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtytfpkima.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gtkddqqnxa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtjmfsbnvl.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsfjluxj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxptivluv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtzhxuzofh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtxrvfhgef.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtorfucufk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtbczcksqq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtpmythmws.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtzpqvhswm.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthbhizvpr.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtretfqasr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtkaaewegy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtonwafucs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtkwvvtvya.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gthywwznid.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtpscqtrfy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtyneothch.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtahfrbsxb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtwpelkjyb.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtsaiplktu.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtrywaycbs.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtqpufkdbo.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtozoptpot.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtvowdgzbc.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljehdoft.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtbjaxggyw.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtjgofxjsv.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzwxotsy.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxqsbgyg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtcrkjtrqz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtrmrqfsgj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtxhvsepng.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtcokokqtc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtpgjnapgq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtdosogeba.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gttozkwlxk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtxwslaywu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtcdztcuwt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtglkzvldk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtoacmpcwl.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtosmmbvdr.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtcnnzrmmd.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtpafwcoyw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtnuljfawu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdupgkou.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtppjqopzx.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtsxsipzse.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtdcqoijde.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtmuvtswsq.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtsinvrh.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtlwvxkehz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtifqnqytt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtmldvntcv.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtlyhcckay.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtcmqjlayj.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtjdpvyyzt.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtbuhpbddu.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gthcutlnur.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtuxqzxzxq.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtfwesbirm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtjpboheev.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtlmgkuppp.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtguiljwpc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtqlmdzdsa.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gthtpzizif.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtbwpcsbpn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtbakfciqf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtwjgzocds.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtozlanati.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrisrwtxh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtdvtwguyj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgozyzaf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtrwuyibgn.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gtcknxbdka.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtsuunptou.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtydcqhxho.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtbtkmmsqd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gthapaypnb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtltwjodby.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvvgfqyo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gthdrgyazg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gttgirjsuk.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtsthpdsoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtkddumtkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtoahmrwnw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtnkaeybcn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtmjntzmbd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtvfrcftqq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtyupkuufq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtnvytxsou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbaxsetly.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpqcdowl.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtodggswpv.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtdimbskix.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gttfjlkpgt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtsxrrbpsm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtwrrtalma.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtvuizgnwp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gthkdwajzz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhurzmft.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtyzgndjnx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtgqagrrky.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gtbxkqostc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtpwzyxyct.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkeccqfg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtoadfymho.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtrifzgpej.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtdutreoln.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gthxddcrpl.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtlbfnefgf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtvwoyyzda.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtjyogehiv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtkwuwcxvc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtbfxbeqju.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtriqedcha.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtzdnssejo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtkfkxzped.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtwypgxjvv.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtqyluzoqt.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtmwjbaimt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtiuwgbqxz.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtojgxsewd.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtumghczaj.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtzwhssbgr.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtqrpvcoau.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtzdagnera.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtznghnqol.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtjtffchem.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtllyeomjp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtilldtpzu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gttqdkrllu.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtopeqnubp.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlxszffsm.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtidpwtbps.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gtprgivuma.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfekwebaf.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtiqrvtnwi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtscksjcbr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtanbbfkpj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtyijwioyj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtklombnvt.html


<!-- 参考信息 -->