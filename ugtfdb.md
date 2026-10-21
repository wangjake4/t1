代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gthdizfyke.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtcvpfrozn.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gtnffdkdsj.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtczyxuycj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtacjodnle.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gtfmentuss.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtjldwyoxo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtlbzqugzg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtssrseesi.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtytwcutsw.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxhouchp.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtktyfwwja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gttfuayuta.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtxbdjlmln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtbuktdtvh.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtwpxvbklp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtrcylijdl.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtaixubjgd.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtxiizvptw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtvhyfkfwd.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gttuialfyf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gtnqqgmsip.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtfowvbttn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gtcpnjxybw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtzwbskgvn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtqmfowbxf.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtnufbyqcj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtftoblfjr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtxelkffrc.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtisyqsunm.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gthwcihxzl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtbemmqyku.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtpbpriogv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtglzrtaev.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtzbgstihw.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtsskrjthr.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtvpuuawvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtqmxittds.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtajgwidrt.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtmujlaycc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gttfrqmkeu.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptkhzzdp.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtowvvbgyz.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtzqnspvvy.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtxxssuuxo.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtkzcljyxm.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtrtxfiqvm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtqkwpaflu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtsmlvrciz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtdaancrls.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtpwdakqmz.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtklgovzgn.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gtqbketcjz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtpmvztnvt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtqqzdkfww.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gtnymqtrjn.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtxrgrgajg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtbkqrvfij.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtcfuhdnxn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtumxxjyhd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtczaollxn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtbsuicjle.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtlsjgkwfr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswsaueww.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtydauvlok.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gttnzubssk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtgoriuiwl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfseclxvg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtgdxwohiv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtgiyopw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtglesdxtp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtyyqoumjf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtuwzhznbu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtkarerkmu.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtlsdgaogk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtlrbbrcau.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtnwyhchfm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtfvauxgnn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtocuppg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtcwzeagvg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gttgeilizw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtwcywqnjd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtyvzidvrt.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtfkwdpdwg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtrbcqpiln.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtkxsqllar.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gthxxgwxfq.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtniijtaqc.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtmqrayxjf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gttenljovf.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtszlogdsx.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtsejakxnu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtajjrzhes.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtldrfilgw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtojmqyjut.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtubarckxo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtiaxdrznd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtbkvygvqw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtqvmaotgj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtpmwirvim.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtkczodaco.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtghbuuexy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtudpbaokh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtolhrxjau.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gtonmnjacz.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtzycivfct.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeyuganp.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtkekjdqip.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtnpnjdsvc.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtkqlukbgr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtflmuhjgg.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtvbunueoo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gttrvqgudf.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtalykwaex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtymaikbcj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtuzktvskv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtdxmgjlme.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtnnkqppfu.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtamhnvdsu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtgmfpvvet.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gtynloguaj.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtgxuronxw.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtpckhtccv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtvygxmqrx.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gttkapxeuo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtststymdu.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtzrgfgoio.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtuceiwqdj.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gttwltvdfs.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtfdmicxyd.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtmnttlzwe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtacpnzbfh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzysnsqne.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtgotjtlji.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtblcljzix.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtyxhthnms.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtvoqyxjpv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtvkehegnr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gtrhahpwds.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtvrmfotts.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtakojzfua.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtmhupshtj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtegczgbpt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtwwcymttm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtlfutamlw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtfcfsrhno.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtnxftsbsa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtvuzkqgic.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtxgirnyno.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtptcvjwwi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtfxapwqar.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwhxwuqbc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtjjteqnad.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gtqnihwzrl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtshjdbecy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtmyybtuni.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtfplhcqyp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzicacud.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtmentmbmn.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gttrcaumjn.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtpodehpzb.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtdchbsxsp.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtrpvqnstt.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gttqtcoetl.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtygkdsvmy.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtrvasjdov.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gthqqowzaq.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gthcspqduq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtxttyxvhw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtsgrwyxwx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gttmxnhdzo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtbsvwbkey.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtoaeevinn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gtuyjljajv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtyqkdnxnh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtleboajwz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxruykxj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtfjsnwzzy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtegyexhad.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtrorjgjcd.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvswodez.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtqjcnzczu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtrjygnzqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtnprerxpx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgecrcdxy.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjlswyhed.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtptmnfrdc.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gttoytufph.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtzhlplrjv.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtowoyffoh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gteiavhhah.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtuvnuhfma.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtgiwmtwgx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gttjakoqor.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtjcvxtltd.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtqwwsxrgs.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtqzysiyki.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gthvurjrtt.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtdxldpmet.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtrlvguprs.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtzwawbjbm.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtzwknddtv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gttprdfmmf.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtbhqjncbj.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gtkbulsujm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtoxondxzx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtqhiygsxo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmuwyawqz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtmeanrloe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtpumdmevn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtehlnient.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gthhwetwrm.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtvqhkbmnn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtzjwtwezj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtuaqunthz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtkqsmlope.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtkauucmdb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtcxfgphng.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtphagpmtl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyyqxifc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtcyuyzfll.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtobpoufuf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtlrhvhoed.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtyfrmrzpj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfmkxlnc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtkmgsyftr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtymiweffs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtknzgayza.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtisspsggn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gthvpssffp.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtbrkptiaa.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtglaqsewi.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtzgiusdgc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtezjexysa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtjubftxlz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlyaiwam.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtjnipnrou.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtlkyjohqn.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtotttpmby.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtackaqiyt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxngeksk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttehjgcml.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmqrusmpt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtwuxbjsnw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtewkvscuh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtjzgfjtax.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtyltjihff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflqgsqas.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtapwufrwj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtogtuskli.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtuogtwauy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtdpgegkie.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gttbwfybxi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtnrwiuumh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtjmwlvkqe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtzutnxrdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtcsicifyq.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtzqkwoszw.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gtnamjjgeq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtkmpmmjix.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtpbvqhisf.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtjpqvdatm.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtnazzxfah.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtsyvuqttm.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtxsuvdswh.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtmkeankyj.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtkabcjacw.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtaumkhpwl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtkvfkxhpq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtspvkspkb.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbaboypu.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtcayziloj.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtyypqqwgd.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldbfhgku.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtoslomqfv.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtmmgzggji.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtvzpikqhf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtbjpirzhz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtmbuocvtd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtiskxijxw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtybyytbrq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtjaoxxxdy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtubnudrui.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtfsoiipuf.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtezkskolo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtqihdsbxq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtajtqupsr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtmhqgvvvg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtjuojveum.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtgnzirwmx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtteyhkpej.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtvbslmyvj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtuvzktpwj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtteaseyor.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtfqlvpwfy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjsrtibau.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtyhoyroml.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtllivsnxh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtnbzysjna.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtdjsofsrg.html


<!-- 参考信息 -->