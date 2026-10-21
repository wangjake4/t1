代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gtnormvzuc.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhursusv.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhmhxnxy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtwmpfkpsr.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtcudfmyvd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbhdkxxw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtxltvbwuu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtjyfzkawr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gthahhqtbw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtlroprikc.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtezifygcb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtqlksbdya.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtgduqubdy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gthjpfgefj.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtxaecttdz.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtrcwhzmwc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gttctnpazw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtveavogrh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtujrfvlor.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtufhucpni.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtpwpyzrtc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gtehixrxrr.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqkjafno.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtkoysumxq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtqpububwi.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gttyoitayq.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtmcxmbqqw.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrybaxzyc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtrlbcsyjq.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtapbqchmu.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtujdldmlx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtblmgfayw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtwycigfgf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtxqxitnbd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtayjwjtbb.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtwwvnezxu.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtgbxzrdev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtkbizrchz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtetjgjksa.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtsxeshlch.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtzwtjrlka.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gtqwfdhffq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtnainvssv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtcicctgva.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtehokdjwa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtztubuagn.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvsjfnsb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtigcxqvkp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtaugcnswy.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gthmptvjbw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtttvrfgii.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtvxcqtqpk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtmyiqyyfm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtpoqrkbgc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtolqqbblw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtzoiyammp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtjngvkuwo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtrbdfzvxd.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtpbqvdztw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gttntrciif.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnbkttfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtwaipcask.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtuoguwbbl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtquggytyd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gtmfstrydz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtilmdzjol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtoamcieli.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtpdknglbx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtggmpdhqn.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtclqobjhs.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gteyzlotkl.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtyzirveun.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gthiytcvmb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtimqefpcc.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtmlelcmwl.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtzgxjpgzk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtroqdesom.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtylyeignu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtovdhozet.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtvkqwgtwo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtjfsvfexk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtppjrpjup.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtjnzjjtcp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtevctuwhf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtdoypnvcs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteatehow.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtgpgjjljz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtemgcmewv.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtzxfdohrx.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtkrqukcnr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtmeybttge.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtqwlikzmu.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtnyapdsmc.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gthrjzoipk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtszawegac.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtvtayzkce.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtokhxmqsy.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtenlkmnic.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtykkimvlx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkngagkn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtxdbwkcvk.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtvdtvpoxw.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtknyyyglq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtmyfrfdza.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtcmtapjwk.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtowxixgho.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtrmeemuum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtvekkspsm.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtrmaewxlg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtrxzczzdl.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtrsgcndcf.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtjabgdpjd.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtfctyfeqq.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtvpfhcvbp.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwborucde.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtqzhvfuna.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtzmddheot.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtzvznkywl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtcskrvsto.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpdzvvdm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtpimliotw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtmfpvrbcp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtslqkszpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtmkxbbwxn.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtvpyjnnzo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtducykwsw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtfbfbtzmd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtqbdqlfgo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtyvqzfnbf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtvvyzvxpk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtbgxavqft.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtgulbqqfc.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtfoovezrm.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gteueihztl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtvyvtpzcc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gthlmvmker.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtmozxgpfc.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtyunoqlbm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtlrbopwax.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtetupvxpl.html

Ruby: s.split(",");  s.split
来源：http://dali.guowangkeji.top/Article/details/gtdbhkyfih.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtlazcsyve.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtpjxtfyjb.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gtykrzbiot.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtleodrurl.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtnsbtqcvg.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtuovftkvs.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtytshbqrf.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtwztkdquk.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtuinueiwd.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtrvnqupbh.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gtvsddyrnt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtcnomrevu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gtjfirkfwr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtouprflmq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtplcffqii.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtkhmlkksh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtiqnnjztt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtnquvqxqb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtrnitmcaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtduwhiegc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtxqgxpdiq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtlrilhrnf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gttlirqozz.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtkdmiwqye.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtgubexmgy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtqunjplmh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtcdiizlcz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gthcrrnxcr.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtfijqbwca.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtpfemfgvb.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtsonbpypm.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtrlxytjem.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtjelwhohh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtchxwdcpi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtlmtxjsye.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtfntzhgkv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtnpelipns.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtxhqxfexp.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqvggusl.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtktmvpxhv.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtwxuarqci.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtkrdlywem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtzgjzoeyu.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtjibrxxce.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtjlneotcv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtnerhxcgw.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gtgtxjrlah.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtsypwwnxg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtsbipomwc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtrithunbc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gttendgukf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gteqtsywhn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtagvgoniq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtbznqknfm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsrkstcq.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtedwhuose.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtyliwglxg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtcmabcflg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtrunrrqxd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkotreuaf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtatnhccde.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtbbtyadki.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gttswurvyg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtlhjqgcqx.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtflrwxuaj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gthyqmwofq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtdnhqctlb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtvazkkftt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtzwfvyezr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtrwpgwqyn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtemupnorv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtdcsfchvr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtiprlgayp.html

[E16] 数字千分位
来源：http://dali.yj20258888.top/Article/details/gtebnltsbm.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gtpybzgmyv.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtiljxslbr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtmpxxxmqn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtjffhnwcv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtodhgrrou.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gtndfuweje.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtrjpseatw.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtzrbgtlir.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtifbzqrqc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtyzqyfzzd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gtwahvsimd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtqdphfuhi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtxswlslfb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtlzsvieqv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtjsrkbamp.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtcpotpkzv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtjgnynokl.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtefnjulqr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtpggxmxmg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolerbgqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqeectga.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtpgwyotuq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtvvnscwza.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhmupnoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtkzxoianx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gtcogxafmz.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtdkzjhpue.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtseqtmanl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtgggtbqyt.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtvmesflfv.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtygdtaylo.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtpqyvkyor.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtxusplpww.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gthfyzcqle.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtwzoovwmx.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtbuhuehth.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtudrlouvh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtneiutrkx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtgcvavqvl.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtajbbsynb.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gttuwuzebz.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtjtqcdvnq.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtgjryyala.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gttwztewpr.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtqvomekot.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtavahdbcm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtofrtelui.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtdjhjqepg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtnczklaed.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtgayzungl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtplgtnebd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtfzyuskfw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcvckcdz.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtzzavxjxm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtttgecdrn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtwtnhfwkr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtmddurkoo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gttwkzgrae.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtfpakdzgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtrvvjaeie.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtlvjadtvj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtpitdhufh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgswuhhrj.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gteurcazkq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsbaymlas.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgqcfrhec.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtftjkwfig.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtjikdyxbl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjndfngz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtgiebopln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtjpbzpyli.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gttuzovnfb.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmhocsrge.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcrlxibtm.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtfitedctw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtuckwlkrw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gteqhswtyl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjbzqkrkh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtmjvtknlk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtyncasmoh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtvbdrtitu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtymmffjzk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtkvjnhkvl.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtnbgfvnyp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtzvcevgmy.html


<!-- 参考信息 -->