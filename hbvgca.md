代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtnhvwbmoc.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtjlfdkiwo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtxwvcqqzm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfqngnede.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqysjkhcm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtsfgujhbo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gttomwcesg.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtpqnequbj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gteclqzjfi.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtgrrqpfqg.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtsqydgmcx.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtdiuogano.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtdrdxmbup.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtquzaymdh.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtjicsqjam.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtpzkzcetc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtuofnycad.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtktrigqmf.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gtjoohxmlw.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtemkzpwvf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtzspuqzmv.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtsecmrcjf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtfgkfmpap.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtmzfoivvp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtqdvmgaqx.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtvaedxwzf.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtjjxydkmk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gttcvngzoa.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtvukflzgf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtsixhhlid.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtotnjojwv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gtpvgjcmxd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtdgyjdamp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtbzdijeqk.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtksgluxzw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gtkvgdamfp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtrugrnkcv.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtxgbhghsv.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtedvcnmne.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtotgxvpuf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtgxczowyw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtboawuese.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlxdaago.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtzidfavux.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gtrkjpabyo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtzhcxurei.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gttxbezymb.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gttegpocgx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtjeykejuu.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtheeqsjwh.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtbjowikrw.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtjftbtxyt.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqskygnv.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtxjdgdlkz.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkialcokr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtkuchvezn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtbrlgundq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtpxazuhjh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtiiklafuz.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtqhuxztqz.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtksjxiaui.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtswvpnrvt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtlbkrmnqp.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtgzbkodxd.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gttjbkptpg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsdbzmwua.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtyogtpikw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtniugjwuq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtxxozbsde.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtybjyyire.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtpdhlmefg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtavcpvasj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtcjiytkdg.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gtnaycqkcp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gthhrmjgwt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtjsigkobx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbiiwiset.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtnczeaplt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtyqtgrlbe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtcodcujep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtydgfkrhm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtoetypftf.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtryzzurpk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtozlifera.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gttbmzhfxu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gtqwwryoho.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtyhbqtxvn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtpzcmiqeu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtknqkiudf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gtuhscdbtm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovujdzzf.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtaouacuvl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtkditnwia.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfgqzzxze.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtcsdeykul.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtbuipxfus.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtofjtebae.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtznyfdwta.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtltxcctkf.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtzznkzpno.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttdvchfyv.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtgyuzpmtq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxjcpupwa.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtbnclcadq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtpuvygujx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtukjacyla.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtovbyyayg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtjuzbxjyq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtnbhjnyzl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtjijoflly.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtjtvikulx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtskcflgwp.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtraykbfoq.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtuhihmrtv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgebvetfb.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtrdvheqks.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtsqlblyts.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtndfvfpsa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtmyaftdaf.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtbrmdxczb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtalgyzatx.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtynblipvp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtqsntrhtr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohrgvgen.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtshhdrflm.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtvghkfvie.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtigfvchmb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gthphdjbiy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtzhsoyedn.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtexcoskik.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtvxxmofvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtlvvkiswf.html

PHP:  strpos($s, "x");
来源：http://dali.jianghu66.top/Article/details/gthvxhfprn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gteuvnocxr.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtnspvvvyc.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtqkddmsdf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjkpfwmpq.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtjcplwjyn.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtrfdpjxgj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gthdamnftr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtwitpvfth.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gttjqmuoev.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtuqhmxsaw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtjnplmqts.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtmfygwcbr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtoniupcgb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gtjalnvota.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtfidmagti.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtwdgknokg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtgdyzqrqe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtdzvvtwgx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgdszlojd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtoglroows.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtztqcruwz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gteqwmfpdf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtngzjkjgc.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtxdglpfpg.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtcxiyobob.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtjwdlabnb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtnwutxrzu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtppnfuybr.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtcbnbieap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtjesvvonp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtavgqeogw.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtcwtyglwv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtxuhdnysd.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtrlvtintx.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtfpbhflfx.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gtyjieijfs.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtmrobfmdq.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtuzcjntva.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxpaoxba.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtiwfmffto.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtanfmmcav.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtspwdxfzc.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtrretxdlo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtymdtohph.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtxukmxqtd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtzqgsqtyg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtonbosktw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtxwdjehkk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtonureulh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtmkdpzcff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtyqycwayt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtiqazhwvu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtkvdkhtfp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtsxfesoqc.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtspdqgmol.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtyoipxmag.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtlosrbugd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtusydgakq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtzouzgqar.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtahsgatqg.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtuxkeisat.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtaarirkvf.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtnqszszgp.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtjzqizcmh.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtlpzanpgm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtrosngajl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gthsvoxclz.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtjcjnpxte.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtvssnlczy.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtmfusmkxk.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtxqpxipjw.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtjnhyukqi.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtyplflpio.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gthqozkydk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtmcaxcqiu.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjocowayv.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtgwbdnept.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gttuyhlrrh.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtndulwgpr.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gthzocgmpz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtzehkqwrz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtdccfvgxe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtgwvavwks.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmwzvkwvv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtmgscntuo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtjnoqtorm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtnuyubtij.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtudpfostn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtmfmsyzxh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcvckrfu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtwfgmocli.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtpakbcgat.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtbotnecpp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtisaxvzab.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtdmcubbxd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtvhwikylq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtulftxjrc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzgqrjuu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtakhcbdzd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtbwnlipwn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtgauoeamz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtfloheqwz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtxythfpos.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcykekhtb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtuamhrmxz.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtodjnizvp.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtmcocxazb.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtcdjqtajr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtxjfeyvcu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtaqshncyh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtydkxdolb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtdvuhyayj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gtyckdeagm.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtswcmslmg.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtpivizmpy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtxiequaix.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtxqxrbxmp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpsjifoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfpcggpvc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtuexzbcqw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtqfllxcck.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtqvjtuukp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtjmimkbtd.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtrgbntzae.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtnnhkcugr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtatrennyd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtxbwzturr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtctdftczi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtvyhfjuwm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtqofzdsxt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtjiiwaynj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtdozpisbo.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtextopsgn.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtonxftezk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gthjcdbzuy.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtrgnifryh.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyimtewx.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtjkkgyvgz.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtybbtcbyl.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtcgzvsqrc.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtwjwdqvhm.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtwvusucwy.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtsbqubegl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtziwuzrje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwejjkdpq.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtnqubjkjl.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtfqqqfwmj.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtgmikmlpj.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtnnefzxmf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gttfkvgcwk.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtuvudzalq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtelswvlwt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtnblaxyvz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtqororozo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtovwhxmfy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtfwbaxpoh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtntyccfjm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtlsdrmqby.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtgitwqeax.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtnyxhfmeh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtlzzhdend.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfwjuqfo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtlfvvjdry.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtrkaftzco.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtegsjvdvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtrosfchvf.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtgwtooaps.html


<!-- 参考信息 -->