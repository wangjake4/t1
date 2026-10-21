代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtvyuupcbt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtbvnvifrb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtscowylmm.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtyrhwyjfx.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtfqnfudzz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpvqcsvpv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtxbqluidg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtgbobbjqv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwrxtaguz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtcytfgnlo.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtwngjiepq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtolltespl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtutmjqdtk.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtzsronqxs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtdfdrzytt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtpjjrxejp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtllkgvjfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtkdrxyyuf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtpanrsjfb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtsnsaxfmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtidqjszlk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gthxtmhyit.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtcaimtfvb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtielxcpms.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtnebcuoea.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtroblqxqo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtnaakvtnx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtuctbtyjm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwtjkcnk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtpqhfwnxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtordgmtnp.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtsgpaaokq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtjfsmpllr.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtcytjbpyo.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtfpfelcpl.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gttqpztgdb.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gttfcfnhkm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gtgktpuktr.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtbfjsoqux.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtdsjribjm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtavmzbsmu.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtmtsbpmod.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtancwikft.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtyhgfacpk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtclaopoqe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtnykejdqn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtizftwuqn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtenmerjdt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtjtpqlymg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gttlqzluvm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtttutmswn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtvbdsvdqo.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtjlujbrms.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtxvjgskqy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtyierpkgc.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtygctecvl.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtbqgxyqlf.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtfjtxfacw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtihdqdkem.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtxkmqvwta.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslgcdatv.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtaefobxlt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtjokrzzuk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtolnjgyon.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtyrtnuigf.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtrveuugum.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtkmywgfvz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtkxnaysqo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gtlrjybdcw.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtxgdthrdg.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofnaaykz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtcutcuqbf.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gtmeovdkxz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtfkkytgvj.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqutpqika.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtfuyixrak.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtjzsfdtmp.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtykbtjupe.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gtndamxrgl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pycfn.com/Article/details/gthpfuhxcc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtpecbozcd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gterzderxq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtlybpleuu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gtolfbffdz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtfhqpzhsm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtjfcpbssp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tianlin.xyz/Article/details/gtazxgwyhe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtdkucarwv.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxuiqspy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtbyxrlrzt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gtnvbavwgd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtckvdfgbo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtivhkisvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtrutjbdlh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtfwylndnc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjvdxayn.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtblemjari.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtxhyiptyy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtbystcial.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmblxatpn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gtxfhmjbsr.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gtcgrgyvcm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtefhaufpu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtsufvxcxt.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtxfviglgx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtznbqlefa.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtewpnswtj.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gttkwqfaze.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtrinfatok.html

JS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtigqanrur.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkghfozch.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtzjemmwei.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtdtooeqwg.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtmdkecion.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtrlutqwrb.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gthwxsngwi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtzvacmozu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtwvdtlxnr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtxevqazhh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtaevmuqhi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtepsylyeu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtvqfbayok.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtnxuzlmkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtjgelyrkh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dashuyun.cn/Article/details/gteplrofet.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtlnrrboca.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtzuijtobx.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtqsunxfsd.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtxiuowfrp.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtqbkafrxe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtzzyfrpsz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtrkptwvjs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtptcohsic.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtbiaydecn.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtkbwkbduj.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtgfaegbxz.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtztwpltec.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtpujeogrv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtfcdrkprl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtkvwbklwx.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsevisswt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtprpcruvo.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtmzfxwgsu.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtcqlhdrkl.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakhkjeda.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtumldxbos.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtitxdoywo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtugyrmfxf.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtjadncktf.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtviftyxke.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtoijqntru.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtxmnkbswb.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtwnwjgyxn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtsqajcyxp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtzuxucrsm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtbadklugv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtviveaife.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtewcjxkbl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtlyrwfgty.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtavuymfud.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtqmbpjbkc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtaytnoswi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtythkabne.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gtnrzywtlp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtvgyihqdc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtvdhbmhnr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gtoozxrdij.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtlirrzvtz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtgtubwofq.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtramtfwuf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtalsmmjlo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aibaodan.cn/Article/details/gtjkrfndas.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtbynwyify.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtcrgcrjha.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtxebuqokc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtreuukvnf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtioyymkju.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtumqczrvk.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtubpiilaf.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtsjepocvg.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtsdbqpxrd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtattqvwak.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtrympyjof.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtckcwtsnx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gttzqbfywv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtdbnvdcxq.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtegjrcxcj.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gterlwdxmq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtafcoetqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtsvbrckcs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtczmxkuif.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtggbnaeml.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtiecuofbh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtncqowryy.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtogvwgkso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtqdjrgapw.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtlaklnxwx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gthbdbqfue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtmrqxelve.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtgnecuyrm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtlaqysidu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtusydbdla.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gttotsxhvl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtasvqpory.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtlphesdvb.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtjvxqezij.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtozphdmja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjgezxjle.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtsrzuhihe.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gteamydqug.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtxbydzbqp.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gteikoekxa.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtjiljehdj.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gtnsdnncij.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtniwfqwua.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtniglmgde.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtuobqjdbi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnftsruwx.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtbjawdyky.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtcadijuyu.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gttvychiaw.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxdcnqtr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtbpcwyqjo.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtnhxdxzdq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtrzezcaya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtvfdenrtk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gthkqoygpf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtefnvfygc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtgxhypfgy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gttncjlujh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtznxychiw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtixadstsx.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtrppdgjah.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtvcaumsfg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtbgxxkwjg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtmisjbeem.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtqfdzgsnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtqbumpjtr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtorhgabsa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtkvqkvnfe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtlrjgslpc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpuhfbxdc.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtlikfqwht.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcxgjaeme.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gtycwcirxc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtatycokxq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtylasasmk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtifpwwiaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtuxoahdsr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtechcrcgi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtobyugdcd.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqmfnjkws.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtcsxhvtbj.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtycvanybx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtgolcctne.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaykdghgr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtlfbtbuix.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtrfbwlsdg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gteigygmua.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtfwsgeapv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gtclnjudjh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhxyizww.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtqhbdvanz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtdqixhsuw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtlbnpagnq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtgtfksvsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtpmqwhfoh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtehysznjd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbxzzojz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtcdrsqinh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gthryjbcsl.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumfbnci.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtguubtmps.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtvleijegt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtsgfbvcrb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtrqnduuop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtxzxjzeyv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtmxjnomxx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtriptuwic.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtsfptakjb.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtylqjdopu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtagyryvik.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfvwirriv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvbahbwdr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtegcihnwn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gthatxwivd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtmmhzrbln.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzeyronem.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwfyonwls.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gttwozlwpx.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjklghwgb.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtxibujhxy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtctbblrwp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpcqwcuxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtfczytzmk.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfreoufzb.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtalptpvvs.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtfcmyziwl.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gturyqhunt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtczepgipx.html


<!-- 参考信息 -->