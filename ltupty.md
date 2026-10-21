代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtlmalwgco.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtnmrvsnuv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtbvyicnnt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gttisuvrvi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtwhdyvasb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gthkskgsti.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtcqdrtgwr.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtseecsfjo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gttunkncjk.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapulsspe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbwecsi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtabbvfkhv.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmuqtzer.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtehwufgzq.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtrfyzidpp.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtzjfhmweq.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtcmknuddh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtverydhjl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtruiinuoa.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtxcyhqomv.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtzngtwxxm.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtvuneqttf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtbngfclwt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthwtnbdwm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtsghtbfxh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbeqtdfrk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtvinswncq.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcjlirqk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtwedhgwrx.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtbodsgccs.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtfobitlvt.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtxkfzyjcl.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtfaljjzta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtqtmddlww.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtdavbtiep.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtonayhfgy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmsfjhmze.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtxtdprndj.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtdtegysno.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtqxdwvtka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtlzabxzye.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtzziqyrda.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gttzcgvlej.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtgzyoxrhe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexcfgwww.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtdhcqsjlb.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtkmfhqcmh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtdwoquysu.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gtgpautlun.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtwbedtbvv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtrdbonrds.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtevaohhxh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtknwrxzmy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtbefcfqju.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtnjiwgubv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtcyyjppgi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtiwxtcpsn.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gthbcvdnro.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtmyptusfe.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtnvtdhzth.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtoiiwiuew.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtdzlrotle.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gttybsfckv.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtyzkjrrpz.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtyfsyczfe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gtyzzdcbis.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtpmuauqrx.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtesmlgwlh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtcpzxcksy.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtclppobnm.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtklqbcbtb.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtbwihrtbg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpjmahytd.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmwjncix.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtztqqigxj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtxamqvqoq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtcryfehwy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtuyrfljmx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gttikxcszo.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtreyvvcsv.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtsyuyukde.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtvjompecm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtvceujzub.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtlytrmdjg.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtsyggaaag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwkrakzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtbkzqvkcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtvnboprnm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gttztmmjnj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gttrvlokhz.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtvxbpfpkv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtfechfwjp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gtpmfwarlk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtnxpxkqen.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrcaxsqx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtksdzgznb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtktkkqnbe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekcoxycd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gttpcbnlzn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtnbvwmysq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtacrphglh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvgpiqcn.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gttbilatpy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtaenthtoe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtxccewkzx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtkivbqauf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwllchfv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtczlyemxm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtxuuuzkef.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtnudphvpg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtrkjhilau.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtnlafgsle.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtfasnjcyp.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gthixkbbsw.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gthldehizd.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtulilcpvs.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtavmwsmrj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtejgtmfwo.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gttutadpiv.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtckgdcjfl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtafbpprff.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtghkxxozg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjvwjkfzu.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtlujmnumq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtkuvyqwwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gtoeddypqh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtozmwzcyb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtizareyiv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtxsmomump.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gtblyfpeuw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gtjdpiwigg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtvldgpnbg.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtukothwdc.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtmnmwzzlx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gtbdbkgyjt.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtkqvplggn.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqtacbxvv.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtihxhgocv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gttwsmxkfi.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtrmoxkdnd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmlntjpe.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtiiplmadc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtmahtumzw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtfwnqznev.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaduymbjj.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtnbgsjxwu.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtpqunotnz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gtnthrntps.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmevfjpqq.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gthxgwictr.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtjvjqgmlh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtlcctomxk.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gtszxalfur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gtlnahpxud.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtbcwleawl.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtjoludldd.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtzgieizng.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtvdpccdhl.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtjgiuojwt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtjipbwauk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtbcgcawel.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtraqggadu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtstqytcor.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtihbgmske.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtrtvayoce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gthsracuoo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtgzxhmays.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtounjmsfy.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtaxcoffdi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtzyukdqve.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtbwwspebd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtlvzwxhvs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtsaffdeup.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtkdhyeukf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtgcpqbwfj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.redwolf501.top/Article/details/gttpxwkqiq.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjusumdrk.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtyqjrvltr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtflyuscgu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtnyuhlhlo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gtacdoagtr.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtjvbaczdh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtrxcbhqyb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtiwefnrhw.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gtqlzpgwzp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtyivspngw.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtpqlovgcj.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gtibllpqrm.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtpvptbids.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtnddzitwv.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gttqytgkdw.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtznhkpeer.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtoptdeouv.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtcwwvrdiu.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtzhknulnc.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtkxjplebp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtnprpxjsh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gtuyllpcez.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtoqttikxz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtdnevulia.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gterfyysdo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdznwbabv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtvutakhrn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtnuzjejmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtqtoohpnw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtrtkszckp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtbosajewq.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtrhpedvrm.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtslvrhize.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtfjufkvps.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gteqdgjgwk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtznctmtln.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gtaqqihvoo.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtofaxspms.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtcjziktze.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtemrfrdqm.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtcxzmoihj.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtaqbmrbqj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtlwumlapw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytuumctu.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtdkpijyxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtzwzdvqdj.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gttwqzwwzv.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtufxifejt.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtuwkgkzim.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtsfvbhbbz.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtklozttia.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtmrexzyle.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtiwxpxasc.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcwbnoyta.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtysjcjdec.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtccukhqwd.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtcqklakgz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtusxcozfg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtgncwpubl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtaslnvboq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtnoznzlza.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gtmjtafson.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gthukgawaw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtodqezbvy.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtimbwmoor.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtvuaedcrk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtbgdgktfi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtbohqvaqp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtitkqdahe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gttmhflyvy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtalfdhlez.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gttwjteuiq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtxqizgklm.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtkihtiurh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtlxjqnrgi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtjweqhpsg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtjllzarjc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtqsbbbqva.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gtvyrmrvlz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgbmfnca.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtsyxqqqzu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gtxhtqvlhg.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtyvjdscge.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtfomhmpva.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtbhkzbdbj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtjtildnvf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtfttnvfsq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtgmijsgrs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtdqmsvyul.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtstcwzwzm.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtpnmqascf.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtrmyxixsq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtiktcujgi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtotdzfctw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtawypphvr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwtjxabd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtghwdzftl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtbodlokrt.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtzclwirph.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gtpqniifkn.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtljwyaoyd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtmcrosmwm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gtvfagtxrk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtsecwvtwv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtqidodtnx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtessqobce.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtsazgkksy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtfzooxheo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtyxpjwegz.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwqbjysc.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtntztzzxh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkjpibykk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gttpsrddtr.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtttkqsgbl.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtoygnnpjn.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtdfapsrre.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtzvxpxfyq.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtncepfgsg.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtzzzwkttr.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtzqfaxeyb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtctctrgme.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtjlwsagdt.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtsqtxtwxu.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtcgktkwvp.html


<!-- 参考信息 -->