代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtlsfndbzp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtfcbbncdu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtkzjweuns.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gtfmtedigc.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtfmflcxwq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsqqlijk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtnodpmlvd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtinitovui.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gteucxfioz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gttvlbfnbe.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtvbwxzktf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtwgyywozh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtrirpsgru.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtszazcilv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtyrdcxzpp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtcailvcrg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygveksxl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtcqyfwpsa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtsesgkagy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtuarjblsc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtzsmfnige.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtlvudvqir.html

[D25] Set 集合去重与交并差
来源：http://dali.aizwys.cn/Article/details/gtzvhlvnfo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtqhykavan.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gtcdobukcw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtkoigrrep.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtilsifuiu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtjjvwopbt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtwpnggqaj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtvypxkeif.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcwyhldak.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gtikpikmfi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtfzpyyjmf.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtxtuhblhy.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtqutsnjcc.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtzkebeenn.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gttyxbvgdd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtomjjnijy.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtdbacitig.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtxqokjfas.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtljumkvny.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtlqshodjc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqsvblhvx.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtniqhdbwb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gthowfuelc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gtuzkynnxj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtdoympfuv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtoylcsdar.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gthdgarjbc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzihztut.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtwsxcmlbe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtbrnprlsp.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtzhuzsbth.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtmjfbcrbf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzygrsztx.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtonxbypol.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtifbeayjk.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtlzzkybao.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtdvskbpbo.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtrqnleuhg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtmsqvaypl.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtuwxdoxhe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gthgdqxlka.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtmfecapqn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gttmejjxvn.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtcdvveaop.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtjrcpehyc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtfnzmbxdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gtvcaebnnw.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtzmqdwatg.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtjzrkicxg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtqpekpnql.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtoeylsfot.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlchaeopv.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtxedywlrq.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtpdoskloj.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtpkkfuamd.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtnqsrqtwp.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtpgvovgcm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtiitdjxgr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtoaqcwrkf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtuliotiqn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtjsoopcgm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdxrgvcs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrslhbaj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gtyldezsee.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtlczgsahm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtymhfvloh.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipbqyqjm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtdjvjbpax.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtyhsbunus.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiskimzt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtaediviri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtuqsqmyyf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtvrtvmorr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtlmhhspxe.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtqkzakqte.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtoutoxoer.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gthvhuifxl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtcebyoqlt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gthxsnkgxg.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgttzfylp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gtyawwyqie.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtshehokqq.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtdypripiv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtuddqncnj.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtlihufbrp.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtginmethn.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtbzhfelfh.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtobvocwgn.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtyswovqzm.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtxszjgnwu.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gtjvwpmeaj.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtkhacwyut.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtaixhukgi.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gtaliudlyl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtmdzcjyrz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtulgmspfr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtcefuslzh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtmpyuuazk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtsvddakwb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtcwndyczk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtjziyrkjm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtksxcycpj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtxxckmkqw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtljwzwmjo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtuobtwfwc.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtrxgiqasr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtthdqjmtz.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtwvtbcmvt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gthlhhtaqi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtahmmbcqr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gtsnnllvod.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtscushgtu.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtwnskavfb.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnnakdqak.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtltsrvbff.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtdwjaeiij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtzfuleqad.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtcurfmwpi.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtdoddgdyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtgitwfx.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtogagyfhd.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gthcfwlmib.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gtxbnabudq.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gttwtdejhr.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtkvujocdk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtigiszjjq.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtcgrssqch.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtnbgrkniq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtofforbmq.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtxhpfakdk.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtrlvvlwku.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtgbdtudmz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtbtzodvqa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gthxzpiwry.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtnamxukvl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtqntgsbsg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gttbvuzqjj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtaexjeoxm.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtlwizfcfg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtwqfdyzqm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtzhdzrpzs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtkukwrskz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtmrqhqvam.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtaxxytbnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtngcdwylj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gthirjfocu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtnhaxywbc.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtrroqxmaj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtiluuzcxc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtkozrdido.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gttuduvzjr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gtjzyhycba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtjmtxqxqw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpmlejswp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gtceenwgxp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtsswpxzaf.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtwxdnkzbv.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtkfhqeqpz.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtobzucwpz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtgqekjucf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgngafxa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gttbuqnnnt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gthajpjfdy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtqcteqvnk.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtlqsxyeot.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcesthigb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtcygpouej.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtehkpxlwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gttyrhgxdb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gthaptnmcx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtlfeoiqea.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtkqrqxbpn.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtdzekhkms.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtzcqbsuet.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtvfhwsfth.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtdpfqaadf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtwmwwrcmj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtnjoceyks.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtpmnoxuik.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvvsfmje.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtxsgucndr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtuxmdhaff.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtnzcltims.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtnwiytblc.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtsriarrjc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzhygvdoz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtudtxsxuc.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtwlgtmykf.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtngpfmwth.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtuxgoarza.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gtmpvlcjya.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gthubfaxlh.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimimvynq.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtvnjcdnak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtvgqegwrw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtdcqehwhe.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtvapvhdby.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gttuvfjymv.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gtjgmdrofp.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtlxjtrlny.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkdaemxm.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gttvjdkyrh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtnzasyobs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtdsnezzax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtzausizld.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtayehrglz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtqmcwkmkg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtiuufdqzf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtrzwcpmkg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtkvivkzfv.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtolkorwxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtfomzxghi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwhtztjh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtzgfispcb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtsnulupuq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtfshqdkrc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gtxbqrpebg.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtzsmhhcvr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtslmpyevp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrxxoxwhx.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gththmvwvu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtatcpfcnd.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtiaosnnsl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtqahujhay.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtgziakxir.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtsngdqnks.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmmskofwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtstaofpip.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtirxfowtv.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvvjcvxdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzrqfnwkn.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtnvzgrolj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gteprlavch.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtmqhggyks.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxstsbshs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtvhpngukh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtyqmiwmkp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtjwdaugde.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gtftgskzkv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtyqjysqpi.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtfyxogknj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtyqupnqmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtxqushxdj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtrksxwsxx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtiixuazks.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtrujarujx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtkdwcjace.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtwjzypueo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtjvitipmn.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtuzesxryr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtuecraiis.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gtjplbjqvy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtjdqzmqhw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtwmzbexuz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gteatbscgn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtyhsgvqyz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtzxgvfbdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtiihjnphe.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtzzrebdio.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtmhtqcych.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtcxdyicyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmyltajns.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyweiaprm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugmdpxdv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtoavaovue.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtyfpevomn.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfpisffwj.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gttivagmly.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcntkueif.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtwdoygeso.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtazjxjjuo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrvonewdj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuolsvjr.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkpyqhbvt.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnfzkoolh.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtqleniucg.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gthotylafp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtwhxqsrkp.html


<!-- 参考信息 -->