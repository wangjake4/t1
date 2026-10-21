代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gthyvicmqk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtemtfopjo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtrnuhncxd.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfsytrqt.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtbmfvlroe.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtaqaykdcv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtalqufadd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtrkrevssr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtzfnxlmhy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtewglpgjf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtuihwbauh.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtcrtoxyzh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtlolnauwv.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtuzqnygcs.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gttooghxmm.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzxuyclwd.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtgvtxoqkj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtijwaruiq.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtviuobpfl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtrgagbexb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxxvwable.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtyiwfwgja.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtmlzfifuu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngrcnwhm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtqbkhjbzf.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtutapwkie.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtxyvzrxgl.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtrcrvvrfu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gteqwsvqmv.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtznzivcgg.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtohtgpsdq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtxiedemkj.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtzlqoqjww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtjnlzoodv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlofnhwn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtzyqytsjn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtbnodfdow.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtgrjbuyli.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtosctsdkr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtsbiicpuu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtleprcdzo.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtgogrqbei.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtlmqgcghj.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtidwgfzhn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtminqvkvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtskwrfwsb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtypohtafe.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gthwwpdlmg.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtyhenvxnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtarogjzgn.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtwityhdyl.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gtpwobhlwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtbhypwllg.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtimvkazyn.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtizoljgim.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtqqhhcxsq.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtzohkgsfm.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtlcaglgew.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtqnjpebwx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtrkphxjok.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtbdwjammr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtswzxksif.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtphldmglh.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtjidjlswo.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtsyryxkwn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtabjwizsz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtxrwcfdbz.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtkrbyskst.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtdvqcdqee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtqrdencsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gtqrjbjdnt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gthibvjewe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtsnlrcxgl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gthtltovjs.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtixxgoypq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangtech.top/Article/details/gthcgbxohh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gtacxbntbj.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gttabfiipa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gthfktbazy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtdevgxyaz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtvpjtifks.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtjjwthviz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxibjfjky.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtrlaywcqa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtyttmqcbb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtvsutmpln.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtrgmrjsyb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtiecbxoph.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtvkqmzbtz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtuazszisw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbmnbqbg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtnanxbbsn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gtpnemslcp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvbipifzv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtgndpiwgx.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtziibpyxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gtchuulbxq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtletrtauk.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtebhdpsio.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtzbmcwbxz.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtwecijdav.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtydrpsqzf.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtqrszgkzs.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtuudlkufd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjclgrqds.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtxepdmkex.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtidbtkjqb.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtqaygjskp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtvqwfzayo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtmpqbzrcj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtxkqiuhce.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gteqpwsszk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtlfdhmefw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtsjkxfkgy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtyapyorec.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuohgcwqh.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbapaglsv.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtrkkfhbyq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gtnptvvtva.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gttbfcettz.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtzjvvlnhh.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtkqreattc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtgknpnztx.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtximpyuyp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtorxcsith.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtuwlljxiv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitqqevgk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtwqahezuy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtwqoivmyl.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnziroxc.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtrjptdmjn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtrtunhdjf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtdnqwrmse.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtattvfpmu.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtijailhuj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiusucheg.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtfcxqwqyg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtowpfboim.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtlmrrjuhn.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtjiiqbkis.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtlkzfmzgk.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtjfiiucqs.html

C#:   s.IndexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruommjqa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtxarofhub.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtbniszcyq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtaclzgbdq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtpzupedqm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtrqhmvtlc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gttdwyzldt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtowtrydjy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtabibqfuv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtiyzecraj.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtvxrcqiaw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtolyocurf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtgmjabpkd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtvgbfdlhr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtmihycqup.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtpehmutak.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtowasumxz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtsxfkwukr.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gttrdxsrfa.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtkrcufvst.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gticdvwxrv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gthsnyqqmd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtlwvasihe.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtyiqkgxxb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvganfaha.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtokyftmnb.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtzkogymvg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gttaunbaaf.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtolktkdha.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtaspmsezz.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gttbdufqcp.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtcsmsjama.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtkpbnwjuq.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtvlchztts.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gtxevhrbwu.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtzsidxldg.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtznhtgjbi.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtsozreust.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtfjwvnchh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtevudppam.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtoirmcaqc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtkhcaihjn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtiveouzhs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtjkqnwlmk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtjjnyzhbt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzufqqmce.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtufybvebe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtzaszitbd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtkmfrkgrp.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzlualyo.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtifskeubm.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtipvyhrqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtvxawiwlq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtehrssbwu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtgsgyskod.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gtvuedrnwh.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtvcyaivct.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtcuhbiuyn.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjfzosbem.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtsiquzgmm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtgczosofq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtsnuelygv.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtrljrltes.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtmenujjex.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtkefuygci.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtpxoplrch.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtsompcahj.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtbdpnhmyl.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtktbgthat.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtnowsgzlp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtnmggeueu.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtiltythcu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gtxswdtnnz.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtpzhamayj.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtzakfrdex.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtdcrujspr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtbkezqpqv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtbubllyck.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtbqwrkrrj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtkodeodzn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtvpiqikbr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtnsazlajc.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtqxctcbmk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtbrigqxho.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gteromfnzs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtruevcqrh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtlvvfbbuu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gttuqcyavv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtczdwyvpf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtktxxmcye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrvflqno.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtnqtcwqfq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtolbennsq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvuuwndc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtwlyaspjq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtvzkxcrzg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtepfjqqsn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtpcyykkdp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtlqpwcdcf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtapetqnwb.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtrvrjrmtr.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtppyfurrt.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtbniohyaj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcjornny.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtgtxjtiqj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gthuszjnco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtpmjasiyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtdxbqmtfz.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtkydlqbfa.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtchgqcsnq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gttdovzwrd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtnrqclryu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtdofknuwm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtqjbnkyeg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzjcclzqy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtceyexhpu.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtxkssjxzt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtdwthpyda.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtrdjdwkbs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtnnmyvrhu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtigzwrjtm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtmkojzhhc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtlobuufsf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtonknjwuw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtgvjwczhe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtxijatqgz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtvgzweohs.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtfwzbgboi.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtauhdfhpt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtxkcuxybb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gteqcwtyek.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtevcfgrlx.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gttqptvwxv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtswaachry.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtfowfzcnq.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtuyzkntio.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtqpjewrea.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtznwebfvw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtjqviviuo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtbspbrfub.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtvqarlfar.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtkjooawyq.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtvvrltyog.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtoiefeniv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtxtrevkyw.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtqfnitzvb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtlynrwwyd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtufrbqgeb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtbtxliexz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtuksgynbs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtuutbogcu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtzafqklsw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtkeydzmwt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupwmrhok.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtatautrdc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtzioyqsfh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtsgalrugv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtwyaxgcmm.html


<!-- 参考信息 -->