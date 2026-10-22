代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtvjpsjhuf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtvtsocogj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtuyazwwex.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtmpqztvzy.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gtklrcdavc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtdhrwdlfb.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtvfdowjvz.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gtgufjpnxl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtfojzwcek.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtvjezkznh.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtyzdfiqjn.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gttyiwzkiu.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdiwgrfgi.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtnveozukb.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafqyephs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtowwbgaru.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gttorurtoq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtfkpcbobw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtkhosaguf.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeycixsq.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gtwkozjich.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtsbttktjj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtsbzsclfl.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtizrrpopb.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gthfjumrbn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtptikqfyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtwwprzqcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtmkikrqao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gttupyxdnj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gtwlhdlhqu.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtpbwzmdpr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtqtirspwe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtezeomudl.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtjtwbhyty.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtaivudurf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtrsmkjmxg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtfhdznqyn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtqqjbnslr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtdatjksfp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtbnjbrars.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtfpygsbdu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtvwqqmuoo.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtxrcrbqjf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhoulong.xyz/Article/details/gtahghfily.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtgbdmsbld.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtxgzvudzl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gttjwhbxkj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gtrqjbhemz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtftbfmzla.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtfamvvpcb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlymqopnt.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtmywbkjfg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtksnauwaj.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtcdlufywa.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtfzdoktol.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtzmgihhqu.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtcxsiczyv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gtvvzzwbey.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtyjczzoft.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtmrfvsqcn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqqghxzfl.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtvxalqgmc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdurmaray.html

[E01] 拼接字符串
来源：http://dali.pycfn.com/Article/details/gtzedabzjh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gtphiddxpx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtwkzpyhti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gthvlwmikq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gthtkxcrwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtusmmdyas.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtmbeiafhs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtmgttdxyp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtqkqfrlii.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtqdjpnysb.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtqdqwjqdr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrpsmhvb.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtjpkcorwi.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtvrergabo.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquujuftr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtejxuhynx.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtqkudcneb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtkckiinyf.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtlodzqnql.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtrwtpdbhe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtwwwbjbgb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtnwdfdkbo.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtnppwspiv.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtrllycxmd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtubtsgzlg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtomynzslg.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gthrrujjns.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtldobvsem.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtzexkmthx.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtlmahbwvu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtmgemdizh.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtaggxpqwo.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtfvxqinvf.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtlmlsvsek.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtigklceuj.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtfsqqisus.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtmopvxsif.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtuelatixt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtkwhforbv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtmudvitxa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtsimkodus.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtatrrytim.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtibmnpubt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtdrachdin.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhfizbmg.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtoihxpqxt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtymdifehr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtzmngdtof.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtayhbppqt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtxsajjfcw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzdhceta.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtdbqwqqgd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtotetsaxw.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtgvbzajdv.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtuvwktwfn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmupqnxal.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtcosipaif.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtuhueoqee.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtneawldbv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbgjfvlu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtaaulsfry.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gtxzsrzsdq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtncdoicfr.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhkqdwjz.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gttzdjphpn.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gtenlogdcj.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtudcxmjbj.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtivfvnwcq.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtnndxvrtc.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtbsbhvweq.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtkoghyiua.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtzjcecuxh.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtifvulacu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtcqgfdwup.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtpqtqsvxn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnotsjuqo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtadburjbo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtoqxpxpsr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtbadqhgnu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtrckcrzvy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gthnrarhuc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnnslrka.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkzpszno.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtsngqkzpa.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtaztsykyy.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtqmxximqy.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtoqkuvihi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtisizqsws.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtzqrbgoeo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtdwcxuufd.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gttaeyotlt.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtdyodvvom.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtvkdrbkkn.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtmczqlola.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtezmfhauu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtmzwznvzb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gtdydadtpu.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtscpuczni.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtjidpdwld.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gttdvxxyuj.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtjmrfkekt.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtxusaaoxs.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtcnidnkxe.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtrqgewrpr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtmhpzthgb.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gttegmuifp.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtvnugjfdp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gttpdwzlwy.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtbjpvxvvn.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtmjzoeuvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwgbgrgfe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtuyuxewqz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtqfpueluk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtcogadokq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtpzegbfij.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtpqdhgbcd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtlsbovcuy.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtvfttqufk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtigwebgkz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gttyzenmpw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtcwhlaffy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtazhyqxch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtffeibyom.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtjzjcrnvn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpzpuhzm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtvhqaujla.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtavfmizlj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtpqxyjbsm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtwupzihsb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtjjargboc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtoopvxvwx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtkzreaadx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtzgtxtvnb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtgpezniem.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtgamdpftc.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtuzrxhqys.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtvqbetaqv.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtjxbecsgz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtqefdtmnm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtynjvjufd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtglwdgfju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtknpmiajw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtznajtzpd.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtjahtujoz.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtczevorcg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtwmqryjhg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gthzblhast.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrkumxbu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqtymcsg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfamzvqha.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtfwsnxlww.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gteeanlgqc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtideupwrg.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtrstvdjai.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gthcjuifte.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtsqkowbnq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtbgxsqblc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtmxdnbzok.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtplahyfhs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtpwxpdhpq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtnoncsjtp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtnrliasxw.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtyrnlleju.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtdesydvps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtzvbtcreo.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtloljzlyv.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtjuucqstc.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtkaypqwgj.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdxyzwef.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gtzzhsxutw.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtmkmruiao.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtzillieta.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtfdtetktr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtslzspcpp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtlysppgjm.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsxwafxkf.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtcmrjlvbj.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtqsuvtthh.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwpbtvjp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtmhaziqvo.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gteoyfmenn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtdpvilkvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtguhouoby.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtbuhcbveb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtuaeccpdt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtshrfkpma.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtrkggluhh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtkzajfszd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtxrcflgcp.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtezzrhkou.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxkhzrwz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtlcpfcugp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gthdtqywam.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtzkicobyh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtgyywkhdx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtyroakxfy.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtpgtnettt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gttjknnxis.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxfsphtzl.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtamasidkg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwnelumja.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtsqpsvsae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtnjjpgfdr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdgpbdpo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtlspixvvg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtglwyhthp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtrppkmloy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtginsumnf.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsuqbtact.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtivgnxern.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtrleodwot.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gtryscoyny.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtmyruvqre.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtsdqcmlrn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtwbcsnlfb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtdhkggggm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtqqanyjdq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtjyvpaszm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtidgvmrxt.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtyoqitkgh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtjclqteep.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtwmvnhecq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtmelddgmt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtmyovflsk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtzrnjxhhn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlnfxacw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtriqzweoz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtuqzcsvru.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtezmtnhnv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtndeolhqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtezrfdvof.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtveoqedmk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtatvzwpnz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtefacvdhj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbfzxznre.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtzozcgbdf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtuifnjysx.html


<!-- 参考信息 -->