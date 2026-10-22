代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gthrlzpxwj.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtbmnvajox.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtnwqaisug.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gteserxrkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbbbbiovl.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtsfwrlxny.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtjlggitay.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtxyzevgfi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtnonrxzur.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gtgfqrlaaj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gtsvlxxzst.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtixvwdykk.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtafshdeob.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtqxqdojij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtajczcjrs.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtwrhntmce.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gtpvvuclka.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtuuulxgbd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtcuznohph.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtduhgsmee.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtoxwkghkw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtnbdpicpm.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtmeuzcflb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtmqgcznrp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gthwuujbqw.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtbgzmxrfv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtoiasvmgk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtgomgxfbd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtvmpwasym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtpanhoned.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtyalathna.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtpuugyshz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtphanselj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtvboioqoh.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtgxsrrzsm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtsvhgkucm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtwkumdyso.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtmraiazaz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtrqftsymw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtffqyskcw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtptlrqslv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtawifallp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtutmfyvhf.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtionqmyiu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtklmvthly.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtcqgszfsc.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtdcilzppa.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtzpbljovx.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtvvbpvbbz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtgynyfpaw.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrxyffks.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtmzvctlbg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjctqmkux.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulxmhvch.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtziolgwqu.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtpcevykyo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtozyywaoz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtnkjawumm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtgctjicpp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtarlmttrk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtmrlqmxmx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtpzsgcxgz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtblprfmff.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbsrwosu.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gtfchcwbjx.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtpjsscgnr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtlywhensb.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtmucczxev.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtykukgggb.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtzkwwsewu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtmsmkgsqu.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtliumkwme.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtwgotrfcm.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtzxdimzzn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtogcsgmje.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtqklicvsi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtrswxzinx.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtagxaapmf.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtzixqtxks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtqunyghsq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gtowobwlwm.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhjdtejg.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gthpryescw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtiolwtdlz.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtqtbrecfp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtwhofgzfg.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtcthatzre.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtiokgbopo.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gthpzgseqr.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtbpszitqf.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtzuefvkhr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtwntpfmtn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtayeyznae.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtddrwxove.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtnkjdptjd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gthrmgceij.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtgmdiyloc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gtxgpdlrkv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtcjgjyokb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtdpkkkizb.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtqqrsunew.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtgclxjytg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtzkuqavbj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtuctwjmdo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfggxyys.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtseckezne.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtyovkalep.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcxkdfbvk.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtavpvuhbn.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtqqrevhpw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtweztclcp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtpeyrwgbh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiafyhbws.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtboikwdho.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtwlvmantu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoltqvgej.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzniopkj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gtzdlnqcpa.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtcwbuattr.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtpfjqbigw.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtqkapxylx.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtmgolaynd.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtflpvdive.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtyqejnitx.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtijldtwll.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtwozsnzmd.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtynkmteao.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtgzpxtdkm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtoqgkdakr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvdtdssc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtxcfclwys.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gtxqhpufeq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtvubbsgru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtymixwqgb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtsggxxeyu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtkxqplruz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtydsrukun.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtpnulmqqy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtonxmfaic.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtatseyqgf.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtrgjzujbk.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtjxryibyz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtyjijnuwk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtmdcvwaaz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtlpifunib.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gttjnqzclm.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnwwthau.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtvrkqcgwn.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtphnwbnfh.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtwafdkfza.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtiykvuejj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gteyoyafet.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtmkussegv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtgedypfqb.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtoureabud.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtjeklyxyc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtwrwswwyk.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcmvnnzx.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtqexaygpj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtiztnmoix.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtobidpjgv.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtwffoowst.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gttumzbqyr.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtpznwszfs.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtcavaqwop.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtjmfwnxhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtjaxeyquw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtvmxkrlpb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtannsscpw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtmeuattyu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtnmrwvozx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtgrzcwxua.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtrlzrqasu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtootwamxt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxmlgdwx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtixvxtkmm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtvmnmcwnu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtgapmqkmw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtbxrmiabi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtnrliowyc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtyfmzxgyg.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gteppfomrg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdposgdkp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gtmrcvkbuk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gtwgpnbgaa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtkcnumhrf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtwiyvxypu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthceklpa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtdndciomk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvygzwlmh.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtnnbomaaf.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtebnrhrrw.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtykyvbran.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtusxrdqsq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtlkldmyxh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtahovcqza.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtfohsjhic.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtudqbykir.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtvjyqlaup.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gthjbcmlsj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtbgnerdll.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtourgbbxw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtodkihdye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gthjrmazry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gtynqzitgf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtxdoxgjla.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtapwvcmwe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtuarrnifb.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtqinmqhej.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtmbcwmwkj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtevgpmbqz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtosfxcbxe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtvarrhsaz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtdefiqrxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtaosospwc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtoktymkpa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtbzpzbrhv.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtibqnqclx.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gttnvfdwvq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjtzucji.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtrohiavfa.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtewbibvne.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtoadfwiil.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtxkrvsrqk.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtisiccrwh.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtiewtcely.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtunhgfcny.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtjdqmvlpq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtzimnpuvg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcmlghkpc.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtmlodmaqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gttztpfpqk.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqlsnzsdc.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtdhkuzanv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtlxfyieps.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtpgdxnein.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtysveaukx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gttgplemzk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtftxebqlq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtluwnsslc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtdhmknnab.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gtodgxxzgf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtmikyyith.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtlqfmkwpz.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gttsnrxhgx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtnsflxfcs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehwyryce.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtjeklicsw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gttqdgiwqk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtvfukpyqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtjljidcte.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtfbrqxfhv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtokuaolia.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtwnnozt.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtugtcwwci.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtetmzkcfx.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtbnciezmi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtgdfcwdzb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyfywfar.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtjxbxdfwu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtzfxwycbl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtpdzexceq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtfpfgmhww.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqutmzsdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjwxnrxrs.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtizmzavtb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtbkdojvjd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtpnqvzjue.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtaicjgyfa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtivvhscly.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtdrxefquw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtvmgsdrsa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtfzmhiems.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtapiygyaq.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtmyyjuvbh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gterimlfpx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtjgxkzbyi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtogardwgm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtryejrcjz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvasisqlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtuygqiqsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtdnehyzzd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtrsviixsh.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtluqmuyvd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtumcqfufi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtpwzolbjt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtdblgrmps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtgtwxvrsn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtfbcqjxwo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtxlqrfmwp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtbzlbdexh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtdsaeztag.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtrfnzkklo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gteqicwfnz.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtsctgmrdd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjzbxovbf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjoospylt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtfrkhogzr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtbecepkli.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekbiwoqs.html


<!-- 参考信息 -->