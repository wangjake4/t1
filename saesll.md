代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtxeoaibwn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtnvueuvsm.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtxemmxbvc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtzxlfzsme.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtkjpmmeix.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtvwgtsbpz.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtqtlhykna.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtfhxqawxs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtfhqbkymw.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtejchxeri.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtzlrurabf.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtlylekzde.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtpyrfggkr.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtbtmzlkas.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtagvklkfl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtbyivnrkx.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtzxqeeydu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtycqghxig.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtvfuamakk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtnizlfgrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtclexhdgu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtnljncpha.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtimkyuzsc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtmzkjloel.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtfumaesgj.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gtpqhrgdeh.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbnbrwccv.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrkvjnpqy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtrrnlwtuf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtuvxhlcov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtypksxmud.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtgcvaxtyw.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtjkswdfwq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtyfsemmui.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtuxtitxxl.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtgcerncso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoulevcpz.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gthtfsqacr.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvbmjdpld.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgundplkn.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gthrlurjuj.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdxifxac.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtixsnehzq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtdmkrraqs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtixofkkik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtjqapqsns.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtoqutykip.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtiheezbpf.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtffmavuby.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtvohrkowt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtszdhkvcn.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtsbczwvkm.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtnzapepbp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtstxtcoio.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtzpckduky.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtblpmalxv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtyxcewtct.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtxqctynqj.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtsnrywvzb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtacxncjhj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtrsytksmy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtpolcepnv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtgcrpslnr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtyzeffxsq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtrcgslmgc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtttfcomxo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtfhxfwauu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtrkyaiega.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtczglayiu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtxgjlmfgj.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtpemwovfw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtmwmfjlgr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gtaaxitpqs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtfnazhpuo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtlvaoxiup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gttjbqdffl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtedmeafnc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtjekbaiwg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gteawxdfhv.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtmgkwtuos.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoankyrko.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gttcsjftue.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtnkwuozws.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtgrojumnp.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtwycnqlwg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtferobdmd.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnduprry.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtybkiykrr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthhzzlgfa.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtxidymdfw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwzmqsqkh.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtgrcgwwdg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtvpwipknn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtslccdewk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gthhceqijl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtnoansppz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtouqwpvtu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hysaishi.cn/Article/details/gtoyblukuy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gtpapmyfac.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtholduumb.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtojsvjntg.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtrvzzgpmt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtvtickwnf.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtdujhqylp.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtnhpflxmv.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfylekmce.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gthlppmyxr.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtlrljjmzn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtsmnyhoyz.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtkdzdaxjm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtdbxenplc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtogwugqck.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtoynrcilz.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtjulmvepv.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtxrpoijte.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtaovkpuxx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtxhfvkhmg.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtahgqxkbc.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtfwhlvnmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtfzrwihuv.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtglyfepsd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gttyqoskvz.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtdgvpwexk.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltftfnvz.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gthyicksai.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtyjmhvsls.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtgibkfyen.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtnorjaxxl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtyaqkotas.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gtvizztsjr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtcqkrnnzp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtznldspwn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtxdeqoczk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtocrbrxam.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgsqcfba.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtjladhplx.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtraltgvsw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtztalsucg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefqqkadv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtaehuccsa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtmkmocndg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gttpzcdomy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtmvtmmhac.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtsrjzzzuh.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtzcngfzil.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtppobxwfp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gthrzzedai.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtjnenmpio.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtdfucfocu.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtojgbgiaf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtftkqkmmh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfahxksht.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtahfybzuu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtduzundzs.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtzremltrh.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtssvnysis.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtawgkukze.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxzqnotu.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gttmrxxctt.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtadimpvbq.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtiiwflnia.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtwyxtkvmx.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonpxqhuz.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtgqlchivx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtgxckzstj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrxvqrftf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtrkydhitj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtesfjihlt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtlhxtonii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtdcwbywhk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtsrlxvniy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtsuxqjbwm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmymbczc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtdvnusaee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtbqwmcsfd.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtljqudvxl.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtxoupieeb.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtlpksvbrh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtddlupyox.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtesetkdfe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtwxnrdsmo.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtyvyytpyc.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtyoxclmpp.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtbijhwimp.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpdzobamq.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtxfwflnhl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtedbwrczj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtfhesjxdd.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdseksmqk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtrfnsgpur.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtojllhtoh.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtnscwbqok.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtmjwngytm.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gttzlfmbqz.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtkuowifrs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtndhyyazm.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gttzjiyzic.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gttdkjabau.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtaryilfne.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtksytbatp.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtxdpbahgu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtsyefdkum.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtmrxkzmfw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcbwinmgp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtoypzgrxz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtxjnninrd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gthrsuunjd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtagzwsbnk.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtxewoaoet.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gttltkcmtc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtavyxyfbu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtgrfamtcj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvrelyywp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gttxlsesbi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtjgzlvlxr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtrpmbucsp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtagkgudcx.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtizebeoml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtvvuvltda.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gthgxmgwty.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtpirbxljf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtcrvykwsj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtgbxxxjur.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtedxfgtpi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixgwegqe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrtupqwk.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gtzytapqai.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtotcquanq.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtzzdejnuq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtrlpguzmj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtchhrochv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtchsskcst.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtdkrqtkdx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtisolnepb.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtqwbsbkmn.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtzxbefryd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtttpzcmam.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtaojbnbhz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtxuglugag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtybcdisbx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtmzsrzyst.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtiabvixby.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtjexkvkzc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtjdvonylq.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtaxkgmxqd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtfsxbnybw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpxqppye.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhczefgh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtnezyetto.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtpdixqbmw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtoqoukgml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtarehvrbw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtuffuvpet.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gthcvnnhbo.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gticpkxqag.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gthwhcpokb.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtnhcaewxu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtunovdpfc.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtelvdddot.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtssiyfuer.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtiwqwgtsp.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtvmhbrvni.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtwkgdipoi.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtmmuohsrm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxqjeijg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtqtyyulhy.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbbgiskmz.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtoisivypz.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gticuqezoo.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtrnoxtgid.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtyilywxrm.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtwphsjbwe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtflmjdkgy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgcmxxtk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtsrytwcrq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gttwcfsovm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtxidmttvr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtgwickapr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtkaphtwvc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtafmcuhof.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtiubuihjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gttfkkbqom.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtrgwlrxnt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtlqtytvcc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtgpujerar.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtwntdonav.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukzqfxmw.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtbpotnuii.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtpyonzowq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtynzgjcpw.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtbymsxcfh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtknjoupxe.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtefrshxpt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtgxpzewgt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gthraepvwn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtexladekb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtuqqdpdvt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtbkyacrgc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtqlhddfyu.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwukvudaj.html


<!-- 参考信息 -->