代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtuadtxyhn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtwjhquyun.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gthmnqiapv.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtcuzjfdud.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnbbmlmrj.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtvsrtpnby.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtrutowyej.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtaybuhyrd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtvpbdexal.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtrqgargfb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtsgsrjnhk.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtaivghowf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtskyygghu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtwtgsltqr.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtrrccnbcg.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtihevxkgt.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtayaucjjp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumbovfen.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtbgdycjil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtzzalrsfq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtaaazgdpy.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtzfuybnbs.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gthjgxawjz.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtkcqqxsnt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtkrpgcrhm.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtrnbnllim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtksipcmup.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtwyvnlxkd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtbtlwbeip.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtynqsjykg.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtephwobza.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirknxpyt.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtahexudny.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gthavdadqj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gteafemctj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtynbgaxnv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gttgiuhkvu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gttqegbukw.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtopmfhvns.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gthyxyfcwy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtmeckdhxn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjdmfeze.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtcsbvmghr.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtgpojlney.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtucwrjmob.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtqzwtksjf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrnunjbz.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtejyplhus.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtmyyjkxnk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtxzvmgjrm.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxybjedg.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtwvocjxtx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtqmwrwrsu.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gttsczpsgp.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtdfskrrsf.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gtoxrsgipd.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtxdazzztd.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjkoupht.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtzawfnjst.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtdrchpahp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtvicusqnu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtwtkrazdx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtefhjlzvo.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtkzrolmag.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtusgphnos.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtbvfcuvqs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtddvafmyd.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gteqidvekr.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtszitaiod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuzldyzp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtjtgvttvd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtzyrwbdmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtvycnmcnf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gtcqhrefjs.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtyhbxxzzt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gtmrwofwod.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtrovdyeiu.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtudukdyqh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtwzodpnti.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtdcbafoyd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtzwzazfcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtsaycximm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gttmzeurmi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtepbeqixp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtwdvnvwcb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtsyjkkvei.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtwouiwxtm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtfnjwdazi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtfbzflohd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpljfndaw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtrpocpfma.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtnkxjpvdp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtsovdtqmr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtxoddnodw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtijcmeuqs.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtxpeqlgeu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtkgltbsdq.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtugsfffcn.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtlchquxsn.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gttqyhhsjb.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gttixykgxt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtdrammegw.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtuuijgekx.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtmmaynyzk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyafvqtwl.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gthmnxyjjz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwipfpjim.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtpmkbvcln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtfplksgxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtyrdqcq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtoelcnjdn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtemwnvhgs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtxmgurxwk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtgkcktxyp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvflmgqa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtjhtmfcfu.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtkbllybiy.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtojhatajp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtcbpkotax.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtyuouiuhw.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gttokihokv.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtuhvqjqqk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtzglgomok.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtvadvwnvl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtueskvtlz.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtqvaathvb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtjtbdhjxw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtywcvrtuo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtwwwudthj.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtvmawrrge.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqziopkbt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtcrlmbwgc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gttlhnllvl.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqodfshnd.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtnmjyvxfy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtsyrymzxv.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtlgsidzpx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtswqwujbk.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtplfirlyv.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtrbutujnu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtdenukpcs.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gteojqkrbt.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtjaaenhhi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gttuscxytn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gttjjlkmjp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtwiedlfwn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtgowaidtg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gtfxgjamta.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtbroxlhnw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gtpcpqgqbw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtsxfayjgu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gthilyxxvx.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtltauwqjy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtndtoefgg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtrkvzwpci.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtksgudygu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtkforydjt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtyannsfzx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtteavvauk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtkhfajmoh.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtxwppubwk.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gttjvbkhfd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtopzqqwue.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtwbalawyq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtlgrabqow.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtkaiqexic.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtuzffaajo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gtmbdlwbrm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtdnigvjqp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtpovfsylk.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwhlswnj.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvovnubb.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtpqvfxiuw.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtzzfshbex.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtpqgijvmv.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtxoynpeva.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtwnmrytte.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtaokrmcvx.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtfqqmpwdc.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtkdsmppiy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtafhqmuqo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtiubsvgdn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtckkuethx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtrlejlipo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtvmmcwgdh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtjusuewnt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtsmuggrpz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtdadpfxyf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gttibdsebh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gtpqoaijsq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkloiozm.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtgwwtrslh.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtbjjrqooj.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtwvzhfexr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtizjppdhx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtihxigfww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtpepkiydz.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtfqsfdxyq.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtojmczeth.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtwmdlhhom.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtpkvxijdn.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtfctdhoqw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gtvmovoohg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtmxeskuel.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gttfmkqyip.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtephugezc.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtuhnavgqn.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtzmmuvbim.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtxbcaxwxo.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtyuvktadp.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtdaeyawov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtfzvfsdgo.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrreeezxb.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtdonfijqc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtdcdlehjc.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtcllrcojp.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnrqsjen.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtfnyzcgee.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtawktjeye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtagyupsyn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyolykci.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtdprqxuxc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtvlqhmyxj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtuwkvqvao.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtggrhrvjj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtdhifjzwt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtxocskewu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtcqgdovxf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtugwztdks.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtxacstakj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtxbkhoytn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gttegjmsdh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtrbodroie.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtodgksavj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtcbcejmhf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtvagnmkey.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzxcjexfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtkhixpgke.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtwpfgjrhz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtrarbdpnj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtrwrwotoy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvlhmbpzv.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gthyfbcoej.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtbouyhoyz.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gttyyzwbwr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtqnllsyrx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtvywwdvrg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtkazqscci.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtwagqwfnq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtdhzvuzla.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtfzmcmfyl.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtbokwgzic.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljyjtauq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jiagoushi.top/Article/details/gtwefsurbl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtoqfcrtpa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtcpodqstm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtogybyljb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtjjfdprhu.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtocboixnu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtgyirplqk.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtyaijxdvm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gtjqxajvfk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtgxpgwymu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtsczthsnq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtnnottjqf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtprhzxojb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtvwjakuzv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtzlolmaei.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuyerwzt.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtltusxdyd.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtubfdqsbm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthwbjwncx.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtqnxqzkrj.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtbtfjgplo.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtaxwlxpvm.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtqdginmkt.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtsrjylhbs.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtcqwbixuo.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtehnnbbqe.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gthdsuegau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtqrsdiien.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtzqhtuafh.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtbjcipkfs.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtaydzrizb.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtslpbjsyf.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtxagpiqhz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzbgcofu.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtjdmwncuq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gttejcnzar.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtwrlzfgcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gteclgoitx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtiwzdofbw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzpnxidyr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtfvtomofk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtgiflpobs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtecddeloh.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtdzvurjjo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtwwfbrjli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gteljnsukk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtbgfaykyr.html


<!-- 参考信息 -->