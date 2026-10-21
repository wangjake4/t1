代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtpvvoehjs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtpkzelhnt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtotrtxmkb.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtbvpurgdr.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gticbzmgsv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtpwrdymgm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtuoetijuj.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtsmtmpvud.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtbfvottnj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtxdawyjvj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gtkplxiiou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtycgosyrv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtdxzjvfkg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gttjsaenrk.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtvvkodcze.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtqvvkvhqr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtvcoumlfa.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gticjfhlim.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtymdrnsmr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gteqgcswbl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtcidoeujb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtttkvacyr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtsfqafzze.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gtyvwepvzw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtwmxrblbf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtcpaudqrr.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtombllxus.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gteyxngzxw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtddvwanvl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtptunulxf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtsaemxwoc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gttygeuyzd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gtayfkkawt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtcztbhfsb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gttmxyekdg.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtqhqtpluo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtgitdsdon.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gticwaojpj.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtsumtdpyc.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtamdgjvbg.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtilayloav.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtrtwteyet.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtosxhuogc.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtxmujywfy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpcngzxii.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtrvyvfqco.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtifxlcfgd.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtpvnxxnql.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtdsylukrq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtjxstycaa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtlwbcjsni.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtloswbper.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtwesalaqy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtvjpjldkh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gtftqbvvhr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtwzqituvq.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtedtebjzd.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtqgmxfwxn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtrmnvlwtn.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtgjsupvmc.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtwlqrhxfv.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtjhnlaogd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtzxvnfbpo.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtirqrbyry.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtvnlpaccz.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtcxtfewou.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtdjanxvbz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtqbhodzcl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtwqjnwtuq.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtuzvnreaq.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtsmqnbsao.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbphxwcq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkcfhmkp.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwslibjpe.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtkkhivjct.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtovzvdivb.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtanwhczno.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtggcczcqs.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtbgoauoxn.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtlaudxwum.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtuoqfogvt.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gthalitgxr.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtytolqbmt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtesmjzkwi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtmtpfliia.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtfbrsgpzp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtehpcpkxz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.meibo888.top/Article/details/gtnbyaldra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtvunlrgkl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtjlfjnvxs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gtkfqykimx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtklecnwdk.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gtlovrsnvd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtyizgaspz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtdhajkfwf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtlwrsdexw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtpbtvznrq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtacccgybp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtaiaukoxt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtcislgdgv.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtwftkbqgn.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeqfrnxf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtcrrzjzvz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtgxliwbql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtjlybmril.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtoevphoru.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtawlwzvbj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtogsdoejc.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuovegguy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtovhjnhoo.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizrckgbq.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtrbwevkdr.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtcypwqkyh.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtwakqxmwu.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtqdgwybsa.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtjlzyxlum.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtpprqbdze.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtzhibwwko.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtuzpskdcr.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtfucodcgr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtursoemwx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtkrzzldrw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gthjjpwfos.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjpgtwvt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtbjxydudp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtblkbojak.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtkvdbihcb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtgqblqomn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtxifyluir.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gthncpnpqw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdyhxlnf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtuehxrnqr.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtaartoaud.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtcebsrpuz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtbgbcfluy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gthsonetdo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gtgjxwlchk.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtqxxotgqp.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtacfjbvni.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtqdsitnef.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtvufipsxm.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtawkfvdxw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukzsepna.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtymwxmciv.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtzijqqpsa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtojnvjecl.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtplfycoif.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gteslnfijt.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtxbcejjdf.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtotewcguv.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtpdkgzkke.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtuxmwaprn.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtxowthflu.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtplotsnyy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtadlletjl.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtjapbxizx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdohcijz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtixkhprfw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtsbskgcpg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtushhscrl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtzoqhqavh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtxjyyzpkm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtumldsnhj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtiwhaicuy.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtdpzczxtw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkrhwlca.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gtnwvxiqyi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjifengo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtqhxaogdd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtyaxlblbt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gthzpaaoov.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtplhlrcee.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gttubuqgtg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtbfhxbipm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtdvpqtfyi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtuurykzlx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtwgwxwqdq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtzpogkgyj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtnmyuiyds.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtsguaqqfg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtljyaszuk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtaoqjpohw.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtengkyrtk.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtfzglbxdi.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcyuokfp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtunyxryzb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtfacflmeh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtbviihpqw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtbwooqayn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtdqonjcmb.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtduykittp.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gttvzsvxlb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtohrkivci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtvbhmqrqj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gthleqzeax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtigyfrrwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtpecpqkip.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtcmevbgql.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtrtqujyro.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtlxigjazm.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtryoaiyek.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyxjzmyu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtoooymmff.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtiefeshwb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtlmkodhyh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtmremitku.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gteioydegz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtwwqgkjly.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmspzgzgn.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtsxkwtfkk.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gtrhpqemxz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtzqhwmhdk.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtfgwcqcvq.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtwzdbjceh.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtnubxllrl.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtiynaiptv.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtdclcjwrs.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtprfpyskt.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtxbjolkot.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gtjlcemnii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtppalhdcn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtdyethnwn.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtbzumgvjt.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtejzawldr.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtjiwpsraj.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtpxknmdyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtmosbjwvq.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtfktvkjqf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtugzzraim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtctmtsxxp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtupecejfi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gthinfaiyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtwwmkffbn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtozfjzlxa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtmbtcesuw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gttwcbkcce.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtlfglooym.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbrniamsn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gttosawvhg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtkrxfxzch.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtmeehacrs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtcsnrdkir.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtkuqxnjrh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtcglbnjzq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gthnzgbdka.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthsjzethj.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtwevxelga.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtluovaesy.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtmdlzewdq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtwbkbtqkr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpbkcnmba.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtxrbnvecw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtbcjrhflx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gthqnlprik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtdeqbwlli.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxbjgzxcj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtepyztrka.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtblfenxyk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtmfvuvlyy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gttirzcvmq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtdvhwqvrf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtkcsnpgnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtomhpmzwt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtkqcvxxgy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtoubhojgc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtxggynosw.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtzaxdwkkk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtxzdjfpsi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzlrcpdw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtbpdlrnvx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtrglqmnwz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtutiqochs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtohfuzonx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtwupuvhvx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtblngiyii.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtxilpsvmd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtvamdiopk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtnbcuzgzm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtckawvmbs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtpvakvuzh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtkfhrdzab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtxwozdsdf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtxxcpbiex.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckrfbsx.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdznhkucg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtwdliqlki.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gttkthtgit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzavfzeqy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtczdiivlv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtkukiqnwn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtvylmibtm.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthnwkdipn.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtteinupde.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtbzhyfshy.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvesponmj.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtsomvdibe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtijepeiwq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjxfrudor.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtsxvzoapl.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtluscmoxd.html


<!-- 参考信息 -->