代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtgozlskzr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtskyclnex.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtjfvjnzjf.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtqmjwbedt.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtygqtmegt.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtdebxlupv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtaelgqkod.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtncmpiewj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gthdbtnjxe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtcwrtsjcs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtxipkhzyk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtiszxcuto.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtlesuxkeq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtyujbxonr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtjgyquxtk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtsnwydbck.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtydiknkjv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtlcotdctu.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtalzsttbb.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gticescuji.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtaxpkcgao.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtnmljvfzn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtdrjcnwky.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtvadtyufg.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtewfoaoqj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtjrambzqe.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtvfgmotov.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gthtvkhyaw.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtkxmfviee.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtzhiqococ.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtrkocicqu.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtoegpdqrl.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtpaodkqrh.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtghlvxhiy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtmconparn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtszteicso.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtaulsbiqo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvfhwssu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtuwvyurej.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtrlkvfids.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtheyobhur.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtdqshbhdr.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtqjidaufe.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtfbuxanop.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtdziyastn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtauruedjk.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gthapjxijd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtalyddvtj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gthompcewl.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtsyeogdrz.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtdnbrpfhp.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtetseukbg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtovvnehxl.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtinnvlonq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gtxifmnusz.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gttsbremsx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtgnufwrhl.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtctpjysen.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtoxrpdzck.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtqnpcdwvc.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtojghxeyv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gthwsbypzf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtduvxdceu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtfjjblhfm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtwzzkgzzp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtwnbmjuqe.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtkebtgnyx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtqbvbrmpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtannqxijy.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gtkyneyegg.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbdzpnbi.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnkrtwor.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtcmzfxksk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtdkavdujf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtyjebyjii.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmbhbqxf.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtvskeubdj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtyasytjim.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gttpmdfezy.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gturskqkqx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gteyjdtwpx.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtzxcsjsuy.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtbscopagu.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtwdtvjtio.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtkabysxhj.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtrutlcxxp.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchgdfgag.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtneyedaaf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtpbxbkqus.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtmkbycdgl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gteuoycvky.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtvnwdudzq.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtwztuvvxu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtnlfhwijr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtianolftp.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtdigemdxj.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gthzsjvfrn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtyxiulbav.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtzzukzmiq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtfzyewiei.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtyhnqijlp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtbfyofimc.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtnhbgicpe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtkgbsphfw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtyezpqkyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtxvcbgmxb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtudetfwcx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtgizjexhw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtddpdegip.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjlgqybst.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtgmzgsiiv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtayiwhffe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtlgxbrwlc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtrmbixkdd.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtxddfheco.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtdkjjhmwv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtjcjwdoir.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gtkyabfefd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtyuzkemlh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtafrzvcwn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtsqpqlwui.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtwhztbqid.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtablaqmvi.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtkpqsmlnw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtszfjrkmo.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtbjjzhsbh.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtekgsesuc.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtvcwurusg.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtvdognuuw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtddqzccxt.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtzanltlnr.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtakermbxa.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlyqfyouj.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtmpfilelj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmgujobpp.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtcfcacavj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtitchdjrc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtuhraopfu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtxgvaixjz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtnrwznyaz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shzxlz.cn/Article/details/gtvriyioar.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtmyaizqvv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gtqlcbrtbj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtknotzrmv.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtjammglaf.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gttepabeco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtoadjksdw.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqyzfgxel.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtsphcvoil.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtamrgevwo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gtrpvddlqk.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtxdxygeof.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtwsmmawww.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gthuimogsp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtcgbmyjwu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gthelvnwoe.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gttvfwmawr.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtxdlxbbkc.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtdblvrmrj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtzhtnctyg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtfzndpyla.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtfrekvnod.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtdnbsprry.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtcjthatns.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gttmztqtef.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gttbcsboeg.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzayvqfq.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gticjyacva.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gtrnoyrywg.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtsjujpvtd.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtzqzspytk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtzpyiqfuu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtuckscxsa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtzuinaiax.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtsoinyosx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtiqjpqhae.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtpzieewce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtfgxxpiwc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtfjxdtsyn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuoestln.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtqkpjowfu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtzaktcqlf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtfokpwuhx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtpbpepbko.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuqibvxi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtrzemukzx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtktchciwp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtyeibthnu.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivhsjbqw.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gthpmlrfzc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtfpbvctug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtvbdfgofu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gteydtpsjc.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtxyhvoxfd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtkktbvmfn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtkynplqar.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gtongiwvve.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtihbgxdbh.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtcgxudvtr.html

Py:   ",".join(items)
来源：http://dali.jinqigfzy.top/Article/details/gtavbbamcg.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtfongoomz.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gticcwwqhq.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtftcqjnik.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gttlfduzig.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gtvgvknayn.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtyvgelfad.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtqegpexlf.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtggmqpvfs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtetlheiwk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtbqldvvdy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtnihsstbd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtgqpdqedu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gttnwgidgd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gtyceawegy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtmjkgchwy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtrqrwipbz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtaftpcrkp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtegnvvfpc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtosgujxwb.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtrmhegmez.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtgwreiska.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtiqsrvcyt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtbgylbtke.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiljqoqo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtglpwhulj.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gtlfnegdaz.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtwvculaox.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtqkgqaeye.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtiaswjzzn.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gthrcruvht.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtqylwrhut.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtzijwmbpo.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtnzzaxtbm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gttdxwxymz.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtsabzmfyy.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtofmdlyzb.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtuftheysg.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtgdnweeyw.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtbxapxofd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtomrjrjih.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtacoscvbi.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtuibvucng.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtwigblpgq.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtrzxikvob.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtgejpvork.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxjciwapb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtsdzpcxyv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtmcbofvvt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtosruizko.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtcquodygg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtqysyjsrz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtfddfdfwk.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtukxcxqct.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtvbglvxjd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtezumeaad.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtbocarbbd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gteygaehbc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtrctfkshg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtxijjggon.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtcozqfeam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtaipnnqqm.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlatnzc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtdbcyptjq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtgillopgo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtggtylkfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtjtpjmtaz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtetwmafrg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtjgyrcfro.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtmxxpqceb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtrwefufxc.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtosyrzhrg.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtrufjdygc.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gtkupfwsao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtqqgzpjfh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtzkmozskl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtdhovrtxq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtjarllunb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtfmtdvtmn.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtabztdeks.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtnybelaav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtjenlvpxp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtqmcbkacc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtnxhoavly.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtccvxdppp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtefavdrel.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtkczqfmjf.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtpctaofzg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtuenuqmsz.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtxtddsljq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtsdalchvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtcxnstbgj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtcwvlfisd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtytmxqqix.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtsgbdnplk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtsieakyvz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtofnubgar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtdpaoywgq.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtfqpqmtso.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gthbfkozoy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtszesmoja.html


<!-- 参考信息 -->