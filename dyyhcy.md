代发 wailian999

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2cnwldeci.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gt2nhbytkoo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2fadhifvm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyfveipq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcvmiill.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2jhoygwes.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2suhcckok.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2kmfirlkz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2yphjfujr.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2nwltwpph.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2aorpcovb.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2jyvdmuln.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2yaklcwok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2trscmjca.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqmflpqk.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gt2tdtkjyiq.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2czpofppw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gt2vrwuyrds.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gt2lghknnhe.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2trhqokhq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2fzjwghlj.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gt2mhwhsfpd.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ckergmfk.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2muymetzm.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2nwnglucw.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2ylofjqsk.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2rfnhnrvt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2nkqcszpk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2tqosolbw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2zwzqdepd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xylfe.cn/Article/details/gt2nhruwnyd.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2fqarmpyl.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2fauzhmad.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2wohejkrz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gt2tsayabsc.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2fnutrvlt.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gt2cdyvtdnl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2osxmhuwl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2ruxwbedm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2yslxmkiz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2ylglrmsm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gt2rbaydpqj.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2geulikvf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2kbmadzdw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gt2szaoaelk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2nntigjyd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2efbkaffr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2tsobyogp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhuyxfnz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2cbhsdtou.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gt2vzmdxcwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2hxhltdfp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2saddogbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiryyukj.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2sqsodwza.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2bbeshpor.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gt2xvinrjut.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2himvdwxp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2dryuvoey.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2bqpksgww.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2ajmtsbkk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ybjhedjm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2iykcgjnq.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2lyynfmat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2ugkkxcdx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2yhwzweam.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2kjuzhtnn.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2lxbgoftz.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptsleohf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2nxnslzfg.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqmkxppx.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2aggiexwy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qepxwmtv.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gt2ooxbawgj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2adymjtqo.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2jilebyhf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gt2orfweejc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2pxvzacte.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2qpjbvdfd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2fdfviawt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2wubfobyd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2yssrcohd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gt2kejxtmxo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zumknqaz.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2xqijsbuv.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2aofjtrzf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gt2smjchlxf.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2jfsqbone.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2bzwhbccp.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2msqhzooh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyadfhy.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2dymywwwi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gt2xliyorjc.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2yinffsba.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gt2iccbxdpi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2gsxuruai.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2qeesttfa.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2dhijdlul.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2baykutqp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2pygwozva.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2mvxxnkoc.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2blbgqaog.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gt2jljyelxl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gt2jpoodbqp.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2pmgdzwpm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2zeipzglm.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2unexudyf.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2kejqzyip.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gt2ksoiqoyt.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2kozdzznj.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gt2hvnsbsya.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gt2hacqbods.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gt2olvhqwod.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncuarkkl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2irmwzbwk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gt2ethlaaqs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2wwqwttvk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2ibmhbyps.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gt2tfbaxgll.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2iopcmakm.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gt2bnyyfced.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2igthosxe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ajvhwuhy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2spltfzxz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2kzqyqvci.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2cfuyuiec.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2iodwfysy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sarsivus.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2lmzpokgg.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gt2gvszutvv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gt2equxuren.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2fzdawloh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2slesfglx.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gt2iiotqgcn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gt2nswmmtyy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2ozmnjtkw.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2clxdshre.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gt2ferfpwkk.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gt2rcantvls.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gt2xvyuxnyo.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gt2oywxjgml.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uarcmixj.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2vdpsxcvw.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gt2bbzcywgz.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gt2mmadurhq.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2rswrquzf.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2ezmdhuzf.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gt2emfheepj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gt2bemzhxsv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gt2gifsxpld.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2jvtsxutk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2inspryam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2bpaatcjc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuywsdyh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxcymxen.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2hlptovoa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gt2ydblaatm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2vsamdawo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gt2eawvmrvn.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2otxuvccv.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2ivxrfscv.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2stegefyg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2igiokahp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2hupdmdck.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gt2lfycqien.html

[E11] 反转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2wccwndah.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2kkerjzss.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2hcqjywpw.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2hbnqsvkt.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2pigxhqij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2yptkypmg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gt2dwktgugs.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2fhyjiydu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gt2hexjuaak.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2xaonqfzb.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxinpwtq.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gt2fqaheais.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2gnfamses.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2vxhnncyh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mudqoilx.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2bagmsrch.html

Ruby: s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2txknahmv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gt2tnnjuaxr.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2bxrvqijl.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2enficleh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2ynprsfys.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obqezypm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2stizawcq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hitfbutw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuctrwtk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gt2zspozlqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2xsfaqtfx.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gt2rpprcczs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gt2kntmqewl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gt2lgnnjpqr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gt2botmauny.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gt2rjchfetx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2dizxjemp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2yyixliew.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gt2vfnhnhxl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfdcjiyc.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2lwuxjyks.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2tzbodkcc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2ctnkeypf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gt2qkjqxpmm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gt2fviyevnb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2pdesfluw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gt2zgadjmps.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2rpyitigb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhxfyaxf.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2vstposfy.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2sjrgdqtr.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxhmcsne.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2fcjdryvr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2vjuwtdlc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2xubpxuje.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2endhzxei.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2mtjqaenx.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2xrrranuv.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkkytvlv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gt2duyvhfmq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2vcapimga.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fuiwoqso.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2fkjsvwmx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2mjjcsunx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2zrzoxbna.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2hxyphdea.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2dkogryqv.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrmpdsew.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2xbxedxeh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2hbddieol.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrmqfkkj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2dspgkmny.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2gxorjjzz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2ghwlupnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2uwjeifco.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2pobnshtj.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gt2delopvtg.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2xnjgebgu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2nwjzedjs.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2kfldnfla.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2alnqlaty.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2nbzcjaus.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2mjtecpgz.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2nuwnjrin.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2ofklblfn.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2vuqefueo.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gt2agigliko.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2orutppig.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2odpglkxp.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rxzilmrv.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2erplxlfh.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rtohfyao.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gt2rysivtxb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2ktifwaqn.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2wbbhdjoh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gt2mehwigxe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2sucwejdt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2oigcmxhp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2mghdjzrd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2smpiqmap.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gt2difuczrq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cztmihjq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2fwuvbtlj.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2mxqlkacd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kavtrqlw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2xvmwdwtc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2qjktvfnd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2cyxhhsge.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfvvzca.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqszrajd.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2armcuoex.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2voediyqp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2waphycwz.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gt2ytxkwijs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dwtodban.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myzxjdcp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2bglptnfp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2qkgynihp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2sswlnsha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2ainikmvo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdgbawip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gt2bazhmpql.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2tidzlrrj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmplifzv.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2qufanefb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gt2wwmrmkhi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zefsonfy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2jmgthebl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2paqfiehm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2rhzcmare.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2gyqygrrd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gt2qebjkzvu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gt2innplgrb.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2hythpesx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2vxpbnfzz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2xceobykn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2gpdyhbmb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2xnpxfpfa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2yeqjzzlp.html


<!-- 参考信息 -->