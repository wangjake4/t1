代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2bgssruel.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcrxowxv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2dlcozjlb.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2azgtyscy.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gt2kexmzkpw.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gt2zmlfdqjq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2hipjytar.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2lzotguly.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2bvgiydvv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2torheaie.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2fsugpttg.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2odffepds.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyeqrzzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gt2vlxkvjal.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gt2throojmv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2hxymqztx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlsppmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2ssdicqwa.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2crzqqyyh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2flkguxsi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2kvebulte.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2pvaaafhw.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gt2urihgwhn.html

[D18] 扁平化嵌套数组
来源：http://dali.tianlin.xyz/Article/details/gt2vvkzgbdb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2goybelme.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gt2mtqxddme.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gt2eihoayzo.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txymnfxw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2igqkizzf.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2jfztpuwi.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gt2yysghigw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqduhukt.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2vapbzajg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxannagz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2ikpsvapm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gt2fnsuwmqo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2soopctvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zumsmjsh.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2qswvkoep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gt2pjbpnbcr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2tdvhzrac.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2vbirogis.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2rnuphlgz.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytvhhmol.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2xvetnmhy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2gnzrpldh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2xkcbronr.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2rbnmzokp.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2ugvangpj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2dkprirdp.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gt2siuoltqg.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2yaxpbwxv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gt2ahzzkwxy.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaanxekt.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2lathknyn.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2dshaxtbc.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2qrprvlwh.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2bzjsmdsn.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2khusdopy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gt2iqhattye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2svblvtje.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2oajsswyb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivapkhfh.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2bwlnxnts.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2rpenmrsc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2hkhveilj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2ilkhlujf.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2sczpyvvs.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2asusaibo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gt2bkjoxzer.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kydppkme.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2doftdcte.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmogoouk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2mntbmrfl.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2ndatwxwf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gt2nrzpopga.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gt2fgaykuqo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2dnsqexjs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2fwgrzike.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gt2dxhsshcp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qjjfknnq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2kzgyotau.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2ndsarrjh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gt2pvxmmjun.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2bxndhupl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gt2xvzmhsdu.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2vftralnq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2syjrkgtq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gt2inbyzoja.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gt2wnptlioc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2ywxqqzhd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gt2djokzcrm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2erdtajlv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2qnuokwby.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2cttvdrtz.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2livylfyi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2bynnxbjc.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2grqknmps.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vimpxgkr.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2ujgwgbzr.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gt2hzxyacni.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gt2cbjzmdtd.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2zfjiryyr.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2mzgdnwjl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2awrdfkfe.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2aazzpyhp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jbuorcuv.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2oxnarnga.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gt2kboixrft.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhpndzwa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2wrjuhhzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2kbhseenr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2zqefdtfw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gt2mbkzwsym.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gt2ltyikvel.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2zpgriuxp.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gt2juffqcvp.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2wqlrcbwn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2ksyskgac.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2tbfurzbj.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2eqiivilc.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2vjvvhprv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2ycfmppaz.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2qwjifkzz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2ygvxvkdl.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eowlxnux.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2gisgkfjl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2fmxhyjoq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2tqloivrz.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2wgbdgtfl.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2jxyxbiea.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2tvpsrpjl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wldyskoe.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2vfvmevkw.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2ujpyfkep.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2qetvvonj.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbjhgxlw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gt2ppidloxm.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2ukrlnosu.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2jrbecfkh.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gt2pxpwmnfx.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2glpeddpm.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2kuwbxotm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daxiang520.top/Article/details/gt2salavaiq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2jvwisxah.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gt2myamfsxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2sbpkwhie.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gt2dknojraf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2yjqyzvcf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gt2jtvnoffm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gt2ybnlmeip.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2ajmcweja.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2neonidou.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqwttjde.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gt2pzewuqac.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2rajoogia.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2thwapbsx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2rlynyfbz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2czklxmxz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhtubuxc.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2gwembgmd.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gt2mxoqghyr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2voaxljti.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2iwmmotep.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gt2rrziwiya.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2igazrzxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2hgmdlizq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2uchfxtqb.html

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2xprtqdyn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gt2febhuuqm.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2oztjtyzq.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2evdxcplo.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itaiweck.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2eoqojdct.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2mcabjtcg.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2otccnibc.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2xefqttjl.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2umjjfwho.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysnamcjc.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gt2xkibszkc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2kjpwvyis.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2cjcaxutp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2fgrrdcly.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2okbmouib.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2wrpwcfyw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gt2qvghpdwq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2fnbpcnnr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2pcfrdgln.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2drsaynzw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2gapjtefy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igmdikjp.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2qzxcuizd.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2ftjfsegk.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qijfjazu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2jtxgjpjv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2mejlrclu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2zwavengt.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2tsaufccx.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lazeuqxh.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2djadnxnn.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2naduguyd.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2sigpxtdg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2mpitaixa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2dvjnwwpq.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2ncqefxxf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzanclcf.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gt2xejoqvrm.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2iiseexzp.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gt2vmerasyn.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2qoebjwzu.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2dllspzlz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gt2ulwxjlml.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdcteesr.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ynzqqmfq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewxdvagx.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqtnnkxc.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mktzeuth.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gt2kxaoncbv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2gutchhlv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2hnaylxaq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2yeocrwrk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2uklvsmms.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2wlhruwjy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2inaxdkwb.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gt2odhedcyq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2nliqcjko.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2isxrmnsm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gt2dbzjfabl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tdtyfnmk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gt2rmifinpw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gt2qzvvcwvb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gt2fbukwiyz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2wdtcqrlf.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gt2gksleapy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2vrpkiueg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2zgoyvafx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xcusczma.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gt2ypvnuqgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2uosigefk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdienuxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2pxijnkuo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gt2qlvatqgz.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2orptvqta.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gt2kgkgngvy.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2rxrmeuwk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2iwglauwx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2pqfsykcj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gt2hsjozggc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2sbnsgyxg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2uvmfnumd.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hzgifcnf.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2rpamrejj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gt2bgecljpr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2xmwcrkyp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbxhugjs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmyplsgt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2avihbpli.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2wbvkikrs.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2erqaatac.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gt2dclubmco.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2bvuxatfc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtkhzvpg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gt2anjvycix.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2ymxhhblr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2xhzzyxqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2acjxrtqa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzwlouwv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2kjnuknxc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymiuokce.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2gpemzyfh.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaxugids.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2ffqmuqpg.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2oswjlasc.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2lcnfkixt.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozjrewkx.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2tpvxphtc.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2isonwzlh.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehbvudmz.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gt2bczldizz.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gt2ljvyibdz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2qjzwfbqo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gt2mtlcccwv.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2cfxyrkzg.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2ejbnfrys.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2oewdqfsp.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2wcnwbywb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2etuiweky.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gt2tfczuasg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2fpdnwvkl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2fhzdzutw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgkpqzyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2rtuzrxcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2vcikesdg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlgyarby.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2epvqsfkr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2caqcqexf.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gt2kiqjupdx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2cwkbroyc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2hrsqjwun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2qvrvgvka.html


<!-- 参考信息 -->