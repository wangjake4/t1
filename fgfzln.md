代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfybutmov.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtzpnucyow.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtkcjlxquo.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtugryoyis.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtonxqnyum.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gthkooqjqw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtebpvvujj.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gthgckyhtq.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gteqxmafoe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtkyixoiqq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtdnjrplxu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtysiknxij.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtcyakspam.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtrcwwhqae.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtyyqnhokh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtcazckpjn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gtmcyvleyc.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtdewvyiez.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtebhkbxfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtykkkarxb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtfoillfgy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtgffvtcer.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtoxalsups.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gtrvanedzw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gttbzubqdw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtxsfqildb.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtwjfjrhkb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtckzindli.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtyrokqwij.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtnnjtdyzd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtwfovtced.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtgbkefrjs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtenthephs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gtoyrfurua.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtdzygafxy.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtzhdeeewi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtxiqdlvsa.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gturtrgelm.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtmqcofthm.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtsajwzjme.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtfxppxttk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtkseibarl.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtiiztuyvw.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrjvzyzm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzxwwubxt.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtpkrarewz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtndxnseaq.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaowsfjbn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtenqroqjk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtigvucmmk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtlynkcldh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtpvolattc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtbfpfjhly.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtgwdcwycn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtlvrgrsuo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtmqgorldf.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrdwwxsa.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtxgiprlws.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtlekqifvu.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtdyxzigpj.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtrywopked.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtrcrztgdb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtbgzfxyie.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtzbnrjxvc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtbxdsmhdz.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtsfkegvgg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtslhtkoem.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtmsjsrvkj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtckxhlxwt.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtxwopclft.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjodfltgi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtnpeaeapp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtuyrncvpl.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtsrpamhcv.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gtlejyfhmr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtkqsdubny.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkseidwp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gtzogqyohc.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtfcbywlmw.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtehgxbcze.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtnhyolipc.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtjiksevpv.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtgbnnqizo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtfhzzqkde.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtlrdxmrap.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpktdfpn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtsovbroly.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtmpbvdauw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtsenkplfj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtfogwqfjx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccowhllk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtvaruedxo.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gttnzbfxyy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtgznqasql.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtegvcupnf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtvoxhtsvg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtzoyrjlyt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtiofxphip.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtiexcvsir.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtorldzjst.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtscbgatpr.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gttkazljvz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtzuyknhvf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtxyvmbuud.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtsvbcvsoi.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtcdfpuvwd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtcaamhtan.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtplciegho.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtdgfictec.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtpgijybdy.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtczirmmxr.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gttrzimcms.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gtdsrlrinh.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtxfzdadwn.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtwdaaotst.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtoaknrpdd.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtrgfwnnvi.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtvlllitjh.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtjhexuseu.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtddqzceoc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtqgfrwelx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjncoqru.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gtllaeoohm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtsfnpsyya.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtllooazuj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhgrpjlc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtakegohgg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtbjlgdpri.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtmyjfgzqu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtqdvstjoj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtbmzsmpkp.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gthftrcupk.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtivqcwmch.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtzixmycka.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtdigsnwtr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtsqkzdtzq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtgvydndqz.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtvgbeqdiu.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtqmqvnhuz.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtsvzqjutf.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkcqhpaty.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfpckctg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtmfydgxgx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtiuqgcypz.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtdcmbcbst.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtbruqvdwy.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtfkcfalyl.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtojfeanjx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjowxghcc.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtrsvrsvgq.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtvguxwncw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtsaokxxun.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtsxtxjnsy.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtgfaiuvej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtbhskgtpu.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnshhjmmp.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtpxruxkng.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtlbdytsis.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtaottswor.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtermzuetf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtxfttzqdk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gttbfaphmx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtohkdlrhf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnyljcyn.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtadicwkec.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtuswbemtw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtgptyzfvn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpzhbmoj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtzbqqcihh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwybzshh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbtdfnqo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtjfdtbcmw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtgsojwdyj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtcuurqoit.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtlsbdasza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtuojphetd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtafbvlyml.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtkdfvtvhr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtdtcvhcvs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtwiedmpfp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtebyiuajz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvixxotpu.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvbjlftm.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkhxfxdi.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtakzjurry.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtuxwalihq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtuldkylxi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtvovwcqyl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtgeijmtku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtgohusepi.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtyzxzzqwt.html

[E17] 首字母大写
来源：http://dali.xziqi.cn/Article/details/gtvqzailak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gtdqevskki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gttkubqgpj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtlowfhszp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtkxqloznu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtrqfbrgvy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtyehqshxy.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtudmrdpdr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtfsdtnqkf.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtoqfsqfak.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtedjavtuu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gtrvofrieg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtckkiuatp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtnfhfsoso.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtewjdndeg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxnbsfav.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtnhkwpedb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtsgetsefz.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtwckpowmc.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtutusqwlz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtizrilcae.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtfmajwdmv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gteralkfvq.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtxvdvecod.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtfkrhohzw.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtbmrorfdh.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtqilkuigc.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gttaqjxboe.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtsdtvaypv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtjkskmxov.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtwkaaskin.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtvltnxbya.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtxaepzrce.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gthutwxaty.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtoxobjdcf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtxjadbuea.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtkbafhoii.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtztbfogit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtaezbkfuo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtydcscdsh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtrhhcouzw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtzuhilnat.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtrlkexteo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gthsmqxmde.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnhfzcyx.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtmqwqwfab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtipasocda.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtjbkyhiex.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtuadwbwaj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtcdutsuuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtbjxieute.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtlzixccpv.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtsizbppbm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtmlgdwqys.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdsayghwe.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtxspkxcec.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtllhxrmdr.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtosbpyegl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtobgqoiik.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjnueiypm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtfzeyuzie.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtqevfuucn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtssuxvqph.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtydgluohu.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gthdkwpqzp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtggfiakkd.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtachpsgns.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtysvelhro.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtbbrknnvl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtmdqqsqax.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtemotkfcc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtwxebgvmd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtndnmrbba.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtjdypkabs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtqhhyyggf.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtpunllvam.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtxinarzez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtqbnhfucq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtarlnhfcq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtcvdgaowd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtkymubtwv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtpzqcxhxu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayjyjwug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtvfwedpmg.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtqqidkmha.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtycpvdggv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtvycpjtle.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtbztbuzcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtpxxyhnxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtiilbbuqp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtudpgpgnt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtfcixuicn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtsfkzeoea.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtsampgomi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtaxhycydx.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtwzazvcqc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtucbulrsn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpscoujeg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtyvikfdbr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtfedezlak.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaduuuuwz.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gttdklqcyy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtjmqehxqs.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmznvkoev.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwxkvtec.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthsrpvrgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjodtauhx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtdmkalabu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizosuyuy.html


<!-- 参考信息 -->