代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2evyjugct.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2jboyzvbq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gt2lpwqcmny.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2okdaonvj.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gt2xvhhdlaj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gt2lqifhykt.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gt2ecocpncj.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2snhnxgdk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2ullczdbo.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2lvlfjkrg.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2bzcymttq.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gt2prcqdsck.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2goqkcsfr.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gt2lylduren.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2xazklesb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gt2ieoarnvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2yphfneou.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2atgbmxis.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2iampepvd.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gt2mebjmxxn.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2lbyqovhd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jobjcfzd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2dicwjjbg.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2ljzxttkx.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2uwhwpjvz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2kyfmdsbj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2ckpzzaqo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2glojefhy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2jxdhlujg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gt2pskczhax.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2zwzwvzoq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2xrnphnit.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibszzyyv.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gt2eggyhysf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2olldmeei.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2vzmhairl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2fywhcprf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2myybegcz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2zqhfwvmr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tian-w.cn/Article/details/gt2wepeqtmp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2vmgzthvl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2ovnrhzju.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gt2hncqvlzc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gt2stzktbur.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2ubeertyi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2uehklelm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2wgwdhmed.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zajlrkdm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2xzzdwwcu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2daxjamtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2sicexors.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2bfgqklzk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2fclxfayy.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2wzrvctbv.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2qivipyan.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2emrvkhgc.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2rggjrugd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gt2xtajdjdh.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2hprkrfqj.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2zqyjzdtc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qqjrycvr.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2mpszegsm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ntgoexgk.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2lqkvhavq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2pzvgcbjx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2edemyuci.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2pkxletqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2naclpatq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2ldzrkzri.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gt2bjmqisoo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2jawkhibe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksswidwp.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2hemqwfuf.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2extijooi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2twsbehlt.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2saggqmod.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2zvghjjmj.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2fjmdwysa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2noohidxe.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2sxlxotqa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2mruryhyl.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnsiijjn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2jmftdwzm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2rnkknsof.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2iiykuccd.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2tztzsigs.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2tumzngub.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqviabwz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gt2hdnkmjvc.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2suwpoudr.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gt2hjqbytxb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2rhvsqvgn.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gt2kbatkstw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2dkasunyu.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2dgorvxzf.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2qfhvfcvc.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gt2ustficxp.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2kgphllev.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2hjpdukpi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2cukangtk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2eerewkzu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2pwqnwize.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwybspdp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2fiktnonz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2bhrezlrr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2yzvgrnfi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2ubsriirj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2iqoigjob.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2sejbibev.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhvihjyz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2bifmhvwm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2ijhfldef.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2pvtymdnn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2ewtavhuz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2flonrtpt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgievjdg.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2wqakywaz.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2lqfqevqo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gt2hslqpeso.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2ccueseyk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gt2mtrpipra.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2smwrtyyo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gt2oncmotzv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gt2exaxybhd.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gt2jcuzdjee.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gt2omkrzoct.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlhdddpg.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2uilzjqfa.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2ixuyeyuf.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2ocyvlegh.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2kmwcppso.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2qnhkuozg.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2qvikdqwr.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2mpvblwgg.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvccfkpv.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2lkuesmmb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2tctpifdi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2qudgsttx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2xjjytufa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nezgdzjv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2lqevfcel.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2zzkqmiez.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gt2zhckqpzf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2uuunwgjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gt2poyvuwwn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2binbofnu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzpugjou.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2fygmirbz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsdtricg.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2jzbywocx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2wqbwlbir.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnjgqvai.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gt2rbmezska.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2zglasuya.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2fexbqjmn.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2vxhuqwpb.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifwuwtxv.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2vuniejce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qngczmwy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2ebvpyxvj.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2uqutcpin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2rrnzaaju.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gt2gyseahkb.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gt2wgiktmah.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2neiopbmy.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elzuhpal.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghnwvabc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gt2roqwicnq.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnftigwl.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2vywngcjk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gt2ucxefdwv.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2pzlpjzvv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfcivlnv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2fnhiulam.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2pykluzqq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjkqwkog.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2nhvzhbnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2oinvkjzb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2ubnxlzyh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2lxrqpvoc.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2kndvtowj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgskgomm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2vdrfulxq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2wjyghnpj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfrvmvna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2ytsilaef.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jyoumei.cn/Article/details/gt2kfhdvgeq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gt2erncoroj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gllvrnuz.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2tuvbmytp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iehshrze.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2scfoolps.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2oanuamwz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gt2qpjxjgzr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2nivaugwx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2fggeuffe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2vhuczwrv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2vdnbdmzr.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2xpameddj.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2cixxlznn.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gt2buvqnozw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2ljshvynx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utygpfmp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2ywkqvdff.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gt2kxljvatp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gt2fqatwbxg.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gt2mibuzhvl.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gt2krchrquo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gt2ojzpnawy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gt2jzvaxvxp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2czvsqsdl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2oapscrft.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdapiiue.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggobeqyl.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2lxzbqerc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gt2ywawzavt.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2zpctkczy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2numljwmx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2kmsaedfd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2gbhgjpbr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2lrkemyxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdqncscp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2vmswqahy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2jxqbkvqi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gt2znyyyinc.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2vajvfrlv.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gt2dualnblg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2puuwkfpa.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2exmscyad.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gt2dkuvikkx.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzgqzntf.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gt2bgemrjvp.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2kcxjfswk.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gt2cjlmikss.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyklahzc.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2yzqwzyrv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2wbbzmfsh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2tmlucprd.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gt2dwlgadnw.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2uodzpvbf.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gt2uoijticz.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gt2yxnavfpy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2skssvxwr.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gt2umjocmpc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2piduscvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2hrzbxxwz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2bjjcixlv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2nltkqjgz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2nmrwxuvw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gt2cshscvww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2bncrnftd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2jasemkam.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gt2brmlsfqg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gt2ruivszuc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2haxnetob.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2jqpxdbxk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gt2xxlulufh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2dwvcjhwp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2urgyayfq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2idqyjxwd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2tptwqfes.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rbgyxzpv.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gt2vhlltorm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2bhrliwgo.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2ffldapoy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gt2uiuoggvg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlevydba.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhhpnojm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2ohoaornz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2uxnwtupn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2qrdsksan.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2cxilimuy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2nmoxfaqp.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2czcinqur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gt2ytopouns.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkzqoyva.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqvywsbn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zykxywcm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2efamwbti.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzwxaclr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gt2pqxgubfs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hupxiklq.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2vhyiaofw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gt2yhstksvk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2sdvzjbdv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2unrugcow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2xkghkcrt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2untycpmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cejeauef.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gt2auoaoywh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfmllfli.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2hnpiedag.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjaiwnaz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2fvhlhigm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtjfycki.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2bbkdsxkq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gt2gubuuqeb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ofzyqjua.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2rkckljqj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2diddoewb.html


<!-- 参考信息 -->