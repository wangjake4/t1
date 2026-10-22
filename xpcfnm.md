代发 wailian999

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtxwfhrwid.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtcgyqzpcm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrkvxflr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtochnbimc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gteuikehns.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezykfyzy.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtbjqpmugn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtlklqhmbw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtaymtfhcw.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtpxfvlfll.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuecbxcqi.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gthchlnswr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtjbdxwwnd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtxffscbxl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtdunzuznv.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtbieoxpbr.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gttvymoqfa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtzyyadaem.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtadcmxvcs.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtbpwarkgc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtncmbrokj.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtapejxppc.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gthnemnxob.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtzyligsyd.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtwtkgwbxi.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtucbsavij.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtpxiftwvo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtdlqvnjxc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtagybghdm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtzarpvnej.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtlowjjeyv.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtafrtrqay.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtsbygfzip.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtpzfdraox.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gthudhcoxx.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gthtuzuvko.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtvvhyqwem.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gttigwbrqw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtvfcacipc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtajyypdcr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilanutal.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtwmcglhve.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtukyhcanc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtkjpohngl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtrynkdahu.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtsxsmdiee.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbhzrufh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtcpzgrpkc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtukbniqbo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtxhnqvrzf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtvxlmusor.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtczthpybx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtnqtvkwwd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtkkdvbqdu.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtwhiuqynm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtjqrqhviv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtanlhrocv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gteoloivnm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gthxxftzgu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtqhbodqtn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtqscztemt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gtjapxpftg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtlwavgulh.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtznmxdugb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtbqrcmbmc.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtpdvkcsrl.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gthllyfkny.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtziadtbfh.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtvpirnrda.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtyvtwgvoo.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtyykyaqqz.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtidzzxrjf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwgtgmrpi.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtvbrfogtf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthoakbuon.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtkdsxtpiw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtymbfuudh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtefxyhkeb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtsldbnjbm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gteuzuxazj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtdiqtugrb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtedoomhbx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtosvcrddt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjqbywixz.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtszwctqvb.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtfnmaixzu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtjkrminqy.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtrzdmeifc.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gthzxskray.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdsevvzhs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtgwahlneq.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtlsstsbyl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnrsasjn.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtniocsljz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtjbfytuwt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtputmgtbk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtmocbmqip.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gthfrkquig.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqjlswzw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtcrogqkwy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtbexyqhzz.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtizxtouzi.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gtrfwyrsfx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtvorhogty.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtawwpdplu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtilufeosc.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtoljtcnqp.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtxwtkdccj.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtwdnxtmoj.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtgkrugqzi.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtmkisolin.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtgympexwv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtmjasohkq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtirhkihfp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtzarenkjm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwgtopah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtdkqdozyg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gthkzbqubw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtnrzyebty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtnssyvuxb.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gtlxmkmxqj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtvcyivvar.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtuhwvbcob.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gteonfevry.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaxyztcz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gttipupajs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtoildfbkc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtosoutdcx.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtuuufcerc.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtihsrjwvq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtetnvkrdt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtjikxhbfc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtzitocwbk.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtqelnukjj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtnlxccipl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtkhoguifw.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtlzxxdsrm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzzxcdga.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtmokjmjpr.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtpjnvkugs.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtlsjatoxs.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtnjhwvddr.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtdordixvb.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gthcxffjii.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtvcptxfhe.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtgfsblgyl.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gthileaabj.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtvvbtudpo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtijwmplwg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtchssrbrd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtneyaiuyd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtuopzhbyg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtpwlkfjpy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gthkhjhxhr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtagdisius.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtughxoeux.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhkmmynl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtwuabwjmx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gturmbvric.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtblffwnmj.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtuvnwmyzl.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtxkanwnvt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtyvsqrezk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtuvljswzd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtecsjjuza.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtunyjunbp.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtjggydhvk.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtipfuluzw.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasrqqmgt.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtobcjaydp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gttivewgsk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtyloxtjzh.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtxnfhuoqk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtpvlamihc.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gterqgznma.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtrkhsigpg.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtopybhdxl.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtglqpaxmt.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtvhlboaop.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gticrkfpgb.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gthxmvgors.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtlcxcrbkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtxmtchhft.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtzixkrfbc.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtdzmxjcqd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtxrzfluip.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtljdcppgv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gthguyfhtv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmqbwmewn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtmfplaojh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtuudydcwr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtqbwfbhem.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtjfffwupw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtyewxjjuo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtpprhrvsu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtucgoraip.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtmhgwnsik.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtluwbutmx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugttzasw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtaaonlwfg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtplzqfwsg.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtyuppjfhg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtvzjpricb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtubbfdlqj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqczdadpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtlczyjfwk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtmpcsfnjd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpskqifyg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxumwzedv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhhwohpo.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtenuhkbok.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtwhvznmvp.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnvxthvu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtlcuidfbf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtlytrvpdt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtmamcbgfn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtwsnvkhpa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtohpytyqa.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtyjnejymg.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtgtvjqble.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtsdhlfljy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtyetncvfo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtiglgghmo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtwpcrbakw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtqhngzkmm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtdxnoaagx.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtcxvyccxi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtqslncaax.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtyayvrrik.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtxpuwhamd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtrftpkris.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtjkyadarn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtbwgiadpz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtoubnznai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtkhkoudoz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksalattx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtjjckwusa.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiplkwzn.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtbxrtnzzs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrbmfjuk.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtlxpabcyy.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gthualwekx.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtunjeofqh.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtmqwlwmbu.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtyxnvxcpo.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtfuclshbx.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtehvronjt.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtswxhmbkp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtkfxlyzlu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtqglvfgpb.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtlxxqexgp.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtzcqnpgmr.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtigtnbpyk.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtxzbueheh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkvhzggql.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtkabspkqt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtdzzsdlkx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtfjccoeew.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtynsimwiq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtsossywqt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtihlgkydv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtjgmabino.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtbjlnhttk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnrocgiul.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtzdnvbrab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtndqettnb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtawmpvhiw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtchejilff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtppklnhoy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtoaieeofp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtedjlujlt.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxvjpcgva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtcbclalcq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmfdykraq.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtsivtcquu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvkwuyqhc.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtkokeaqiz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtyxcnvfxl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbxtqeqfo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtqczvtlmf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwwtqbex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtlwwutfpu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtfbeedqrz.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtsgkedkjk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtevydadah.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtiwarjujv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtzamkxksp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtlsuwgpwa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtiynwayft.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtcqasbznp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtvykkxbvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtfzavvkga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtuvaszybv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtvlflrudr.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtbcbcxlfz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtoxlazokr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtbfmezwyz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gthiuyixmc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gttwzgtbez.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtvurvusux.html


<!-- 参考信息 -->