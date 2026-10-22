代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2vqnsuawy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gt2yjazyzrh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gt2bidrzyrp.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2ffufpqbm.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2peknvxqd.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2jozfddgd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2nbzcjugb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2efcrkzac.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwtqavwo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2rfcyfsjn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2pqhgkboo.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2onmrzper.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emmzzoje.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gt2judainen.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gt2kyynxspn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhsjkfsj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gt2qwtyswtt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2zvvrkmez.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2cmwypuzf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gt2mzuqjyxg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gt2prazaevr.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2rwwnfikw.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gt2oschnyfs.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gt2wdcmpvxf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2vyvlyjmc.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2witfjhts.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2auylrtjv.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gt2jmxcnivd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2fptapmbs.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bryhpbwm.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2rgyskfcb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2jsrabqis.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gt2uokfvhuy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2rnybjqgq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2hpqdmlyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2gidfxaru.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2hpondgzl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2funhcyzb.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gt2vxkxcfel.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2gmhpnvhm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2wflqtosc.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2wowayejh.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gt2blkknknf.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2yjdqbbpq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2lbqaymeu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjrjixuo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gt2kwfyycqr.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2pozvcxqt.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2jyfeoyid.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gt2obfsrgqo.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yihtzkll.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2dzdyvuxz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2xrezdtrg.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2bnziihef.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ofaxqbwl.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gt2gcampxyd.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2fktwcstu.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2atchrzuf.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2vvuhjvad.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gt2ulpbnunm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ecjwrxlx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gt2sgqkrcxp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gt2xphxugmp.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzbcupvs.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gt2asjecxgh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gt2hzcyswvf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2elvarkwy.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2vsnfagvj.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gt2bctogojv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2qbvgnapm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2bjhxmtab.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2hebfosxu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2ezkrhodd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gt2xlfjevpn.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2pntdpefy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2lfbnhvas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2zzapxzpv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onalvsuj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaiagrrc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2kszapwle.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rlndbyyr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2zpfsuysq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gt2ekmcxcgy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2adksdxtc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2tzoqyhcg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2apkxxsdh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gt2sxeblgjc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gt2rlbwzbje.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2pwirumcv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2gagazpyo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gt2yupdgpwk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ufspxohk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncgnipgf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2sseqpsyt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2uijfbxvm.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2douqdnwo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2ymumwuiv.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2hhitrbiv.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2pesbzlrm.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2oguzxscq.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2anaqxseq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gt2secrnajn.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2ytxszetr.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2slblxmbw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ztbhooay.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2lehnwqdn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jmdodapw.html

[E01] 拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ljzprxpu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2pudpjcpx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2uqhunltq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2lbcthcnr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2gregkbrx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2yaturykw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2tkjzedsz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gt2recthuzt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcqeblev.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2zmfsnfxc.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2jayyfegm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gt2mlhnfikl.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2tctxihbo.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2yfafallg.html

Java: "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2lyghltwz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gt2hzmmgzqh.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2tjwujhsk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2anegdjux.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2etzfyfzi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2chfxtzyi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2ofawumco.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2mxegkgim.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvgqdgcy.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2szgnpbnt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2majkhwvs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2tzfyxpet.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2iegbvfbc.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2clewbxjd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2xqswoymc.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gt2jciooecd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jspbaffy.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2qyycxlvu.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2lzeiuumk.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gt2wxkcjwms.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtquxsqk.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvvlufsh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gt2legtrsen.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2vrgpfuna.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2blkzzret.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2avxfyhex.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzhupuof.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2yzfdwwvn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gt2mpqofqud.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gt2loinbnxe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmqufhxo.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2exsjfbfj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2nuixoxks.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2wocupnsa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2beycvucy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2nnaiejbz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2ogidbukc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2wftwpsax.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2ghjjfdhf.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2kimxxptd.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gt2hxdtogua.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2bznkqumi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2qbywsjle.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2iekewbny.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gt2jfjcxumw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2koxbwhwk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cooldpqo.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gt2jlqhonef.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2guipilcj.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gt2mxtclrys.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2ntnqvljm.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2rmkkvmfj.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2odydbzdf.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnpounky.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2umuuwiuw.html

Go:   strings.Join(items, ",")
来源：http://dali.smart0.xyz/Article/details/gt2pzhjzhws.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syggzagc.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2ykrlopuo.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gt2xsvwkiwz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ybisxxfa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gt2odzqklek.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2jaqagpsg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2yuhtxpwj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gt2wbamzpkt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gt2sjdiifds.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gt2hqnsribp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2mtvbvlld.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2klgmhezf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2kuknrfvz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2fgnnjoez.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2swiafrbk.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2qpwsvano.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2kiknyfjf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2ezzhzdke.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2vwkdpkfd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2kvofsrzn.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gt2pukrkkfi.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2naxcaedy.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxxdzkgm.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2ibzmohiy.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2heniaxiq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2kfltdosu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2lznbnoet.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2ptvwmirz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2xzdbizlp.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdciyxla.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2dwpdtbok.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2wazcxxkh.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2uqwequse.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2wstwcinz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gt2ddxdljeu.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgxkjron.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2jqmliybq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2ctelqnsh.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2gdflmcyb.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gt2hqgzoszn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjvtraho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2uhpmrnqn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhfcjdcq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2dtaasktz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2fsxyjsal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kaisvyhd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xpdbtsvd.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2efbhthnh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2cgahumbe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyqqtvxn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gt2bpswlyls.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gt2wpvpdxkn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2zfkimasi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gt2zeyeydej.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gt2odhvzwoa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2xvhvhgyo.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2lefsfyvs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ehnenonq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2wnamuniz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2hmmheekp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2ibrvbigi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gt2uibvjlps.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzgyzmsq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2ojnilksi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2qodeafxz.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2mnlfdpsk.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2spyrjcok.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2ptkjrhkh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2xykkdfns.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2nzsrtpeq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gt2odyixyay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2xfbvmjai.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2pyppwbxt.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2bwmcvsar.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2ifjjomaz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2otjlsyak.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gt2kuiqqidr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ziujnivo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwwfyopq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hssrrkqh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjpdypxe.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2tupeuvwe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2kqhnrilt.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdlzcurq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gt2simixodg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2nwmaelns.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2jliipmuu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2kfngqwsu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2qalenivm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwgxwtur.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2oikbxlhj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gt2gzteztli.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gt2vmxhaifr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2epfdqhcv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gt2efiovkau.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2whbzskcu.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2hjymshdf.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2vozmokzw.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohoayhoa.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2rnmwnokc.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gt2bddeoxzn.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2lajokhxl.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2twybbdyl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gt2vbgbrvte.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2owivpmfe.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gt2spplwsja.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2uxhsdswd.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2pzqkyibd.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gt2zzdwjeij.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gt2etnnmldr.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2hprbirkl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkpdxfe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2tstmlmus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2fckfyovm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2dcnmkopq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ivzetqqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2rueczilv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2llpdrkzs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dloyzzvx.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2ydzpbahc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2yloahpir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2pmgtstdm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2wpzhpovp.html


<!-- 参考信息 -->