代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtryqncjru.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtxrjedzzz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjjssvht.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gthaoyovbd.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtvwuvganq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtgpcxjxtw.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtfyalpipt.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtfgihosuc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtupbgyjiu.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtznegrbss.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwmbccpuv.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtwzplfygt.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtsylgzzkb.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtgvhaprmy.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gteyhmgsjz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtkrssiecq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtjasvwawt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gthcxvcqmo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtxyjnkfvu.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteegyvomk.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtvhnstikx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtdupralqt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtrqvgwxku.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gttaggkmvx.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtpxkimqhj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtyloocrhm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtzuqwgqwo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtbxlxkphz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtwvhjycji.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtxjiwhnrj.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtooielkgu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtcrmxnwfg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtxgpbazrx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtaohyoxyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtpoavkjwx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtdtntbouf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtsuzyybmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtehpagmjb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtbhxoiuvh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gttponjdmx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtmcfbkswd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gthtpljgtu.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrgqbflb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtnszhzefc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtclllcbmw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gthwuxpjwa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gtvodzdutf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gttvmojhfo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtedjhjlym.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtgpcmusbu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcosnqeye.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtirabdzad.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtllrugswz.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtilasbplj.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gttfizgvsy.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtcsxmgitl.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtnzuubbun.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtqbivxiem.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtjybxtsqj.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtzqgnejes.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyuhsxucx.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtrzngsije.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiroeikxz.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtpkzpsdsa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtrrdelnnl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtnqfvblwc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtedomzxki.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtdtgavfio.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtesissvnf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtgpgynbnl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtwprkhnaa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtideprkkx.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnufhszlh.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtkkcaenvt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtlanmbvbq.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtycqmqbli.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtligfzsrv.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtubevpifu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtcugpwhka.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtucrrguyv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtzmpictbv.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtqcguhzyd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtmavlaaaa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtlfbpxxen.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtsbqrwkob.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtflorgumi.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gthaaptxtz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtvihhoygw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtfzmcptle.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtfukxudzf.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gtrtwsxabp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtqzgjeono.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtqigvdssp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtsrnqlqqf.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gttnwtgwjw.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtwcchcvzd.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtepiwawhb.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtnsklgjby.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtvavcqbip.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gthqnrdnfh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtirwlddwc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtoarypgfs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtcnqrywnv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtzvdrbpzk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtlbneqzjw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtasivekig.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtawbnsjis.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtdovcjlfd.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtylcsrfzp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtknyqljlk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtfpjurrjf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtylobcvqz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtxroerllq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtmoykgcry.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtjyaqonui.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtekwddkvq.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtrrufntjl.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtwugzajuo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gtguimrgim.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtubqbznfh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtvmmbdhqr.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtuvyvnizv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gtdvheyaoe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtuoqbrzmc.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtkwsyidly.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtsblnjzln.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukckdibk.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtamqkusjd.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtcvxpkksx.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtkbzeqgvu.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtyfkgmpgt.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtsuxawecq.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtftuqiprw.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtwdgajopl.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtqxrhhedh.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtzjkxqald.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtsyrhtooj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtgfuljfba.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtrkyvdxmc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtpfaqymoy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtlwuceqxy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtjlotgaza.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtprsxsoox.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtdltvdpwn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtahwycxqt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtgbcnpogs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtczwqoslq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gthpkkjaws.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtuwiirmnp.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gttctxuspw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqzfsyve.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtlpztkjml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gtekrkahjc.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtlxqvjdoc.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtmgonpkxx.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtrlzdhpzv.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtfziidxvt.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtvtvmszha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtjfbpmsfw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtvkxnerbn.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtjhqfzsqu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtiooqbjjl.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtxtygnpht.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbbmhfae.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtxrajumbf.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gteytpbjyc.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtxaaxwlzq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtnxtyermh.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtziycbtgg.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtuzleetmz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtzcoyyprg.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtimkrntqw.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtrupcencr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtbipwcopy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtojrouczi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtetudoqyk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtzrgigxpz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtrmhlclkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtnuhrfnsp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtidctnimb.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtdsmrdwst.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtqaubajte.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudwxssqt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtyveovskh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyvhrestk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.birdmap.top/Article/details/gtweufiher.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtwlaiugtb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtjuqqkhdj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtudawvded.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtsicshwkv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtycxontvi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gttzmjyqfv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtijiowraw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtnyrilnee.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtfnxlnebl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtqoyeegrf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtmcxsgaio.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtpyikuzcv.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtmjlndxjr.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gttkbqqanp.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtuwpepwwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtcbaqfizg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtlgvgrwfs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtxkhgorql.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtosxfnbtu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwlnclkk.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtboclpzfq.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtszyuruxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gthqwdktkm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtylgpkbff.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtanulario.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtdjrmksmc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtdklpefjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gteeakmnez.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtelmjnkyy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gtfhdbnhid.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtbxbymoqz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtfmayzuls.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtpplyfxye.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtrlgldqos.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtpltglmch.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gttkldqcmz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtagewmjlu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpadixswm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gtwzqwcgea.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtforsygot.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtgforgsfh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtunislhyp.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gttookjicd.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtklvluvff.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtilltkefo.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtuocqqlgf.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckkdvctf.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtyfrndcqx.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtuqmjlcdw.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtqfmoyinc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtcpoosghh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjzhhuxc.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtbfaouczu.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtecliefnf.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtitajylel.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtsyryfgjs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gteoqiqpdk.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtxyrjzqba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gthhxmsafb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtkckzvcjf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmcxrkgf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthtjnnhs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtadusaplc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtmrxnmbfa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtnlpgtxkw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtakryyfcr.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtkiufegjj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnjuczcu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtrnkarmoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtyghgvodc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtdvioxprf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtfuimlyxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtpxerinos.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gttepilqxb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtiwxahvlb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthdfxevvn.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtgqrezsqy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkteduoxc.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtvuubmofv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtavgwuzyb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwbasiagv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtmpctbtrx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtvwnmideo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtdvqjglzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtfiarhtch.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtanszzibr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gthqwkaxhk.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gthwnbcscb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtsojyowcz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtggiqljfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtzcrykvsg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtyqjeglub.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtiexauugv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtwopmzuip.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtzpzscmab.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gthvborgul.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtqxtjkqwp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtfmtmsfhe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswwjbfaq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtcytfjqvc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtchrmpbfq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtltdpyrrq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtfvqsklav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtmodevavc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbxlxyir.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohplbsvj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtrvcdjeom.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtksficurg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtixnwpuze.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtkjithuot.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtgnktujia.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtdlejwdix.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtezivezok.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gttxrytanz.html


<!-- 参考信息 -->