代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtsywhgyua.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtpseyllxs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtqscmgpcd.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtgxkscjqr.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtfldyprcc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtkzqbifib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gtiqupmoka.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtogjrnteo.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtivvnjkyi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtqhfmzotn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtzxgqgdtr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtamajiolq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtxpyssjac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtndwzwjxk.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gttqrglnru.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtbdtbsltj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtashwgkde.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtqfebdsks.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtuausfyvh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtyndubsmj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcejqddq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtfvqxfuhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtvtjqxits.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtvzlcpkrc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gttdkqkzlk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtxmihynvi.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtjemvyouo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtlbplcttc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtmymiyapl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtpnmqfcmv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtdeqdjsrt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtamctcjer.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkkhnjck.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gttyhwcajc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumqmaosw.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtiadxferc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtdxipsiiz.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtgcenelet.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtqsznovid.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtmfxzervz.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtpgigbene.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtvjcmpoys.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtqaoeuhsn.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtcnbsjddo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttlaxceli.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gttaldgaqf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtugcvbxte.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtcsvaeuuc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtprcuvpbx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtxytoctjh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtifomcobf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtxurlfnop.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtulgpzvlo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtkhydofis.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gtyezoxtia.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjaowpbz.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydenlbsj.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtaitzhhcw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtlfwisqhd.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtsrtbgzul.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvcenbku.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtvhfrkxrp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gttuqdzklk.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtyxvncbts.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtpkeklmgo.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtoekfladi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtzcomzdin.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtdjwhvmbo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gttdducupz.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtamsisclm.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtgumqjvvf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtmplvwfjp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtkjxueyov.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtyxvaemuf.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gttnzlwkcc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgeubxal.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtcxpcblqa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gttxbgombp.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtmklplcgq.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtchrnnvmx.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnhrqqbi.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtyijitcah.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtfoesliwy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtmhxaxaje.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtchekxtue.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtqadvgbdb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtqwcluqzf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtmwdgrmgw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtswcegdgs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtbxkgwhyf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtaqsmtybj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtjtrfeckd.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtqiapfcms.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtystgrmxt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtmemqlskd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtymkfbitp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgctwoyqn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtkkpiuadr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtzubndceq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtdshmkvsy.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtqtzzrerx.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gtcefyyqal.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtfmbnhqie.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtavleliqg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtacjxrkhb.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtxjgcndhc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtyfgezxap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtzikupmij.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtmgfnokmr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtsidjvdgm.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtcavwctyi.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtgnpqshiu.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtarzohjyd.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfgosgjp.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtzjxergle.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtvmwvaijn.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtwnskvjbr.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtcfuophux.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtfdztqauy.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtdjdebxxp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvaglkls.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtextmdhsz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtipdvphca.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gteyifuyzt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gteujpntwr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtzjflnmiq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtmjiyaxvh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtdzckmxne.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtvwagqgof.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ivvv.top/Article/details/gttsaypyfy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtprsojmij.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtwjeyoade.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtzaocwqia.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtcpnmpigz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtoqzxckil.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtszkgbrdv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtnalpdgts.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtrvcurggg.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtbblokkbk.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtrrgkqwll.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtnbyyscjs.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtctzoazhy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtkzpigjim.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtspjxahkx.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtufjhdkbk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtlajcyuhv.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtehijpmlc.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtgywnkdpw.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtgaffxamb.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtqbwgpruv.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gtzjolnley.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtfgxlmljs.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtisxojksy.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtrchtchmr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtkcqyyqnb.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtdukebiiq.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtefyhhjmn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevanvvje.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmfyafxpq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtzmhtvzox.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtcreawqhz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtdatfksfz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzsxkzcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvfuzeab.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtuuqhhhfo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtuzbyujtg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtqdgwreko.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtdgpcbzmt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtfqswdncx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gthrkublbl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtarfcgdyr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtbssrwnyk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtnjnvbxor.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtjnsjprjy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtoywvzqnv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtmdlgrvvx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmlsitaar.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtthwnbaau.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtodvnciaa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtlqgjtfnk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfjfjvsvk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtwvqnatkq.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtvkjwslph.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebncxfyc.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtxcuwzhrf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtrqxvqsgx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtmhjqepxs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtuwvqxxcw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtqkmdfufs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtkxlardrv.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtdmhmlcew.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gthdtbwvvb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtevdzrixz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtcnyicics.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtidiqtxnx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtrxvkqpeq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtiwuniyha.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtxnfdwcdh.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gteelfcelj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gttxvkeryc.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gtdtfkzirp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtifikjaip.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gttrxgfcgw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjmalizn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtxnigwoai.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtsnwqrmbu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtiiuxddmw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtcultsbok.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtqjudnilf.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtvtdliyve.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtebkkylmk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtvgsmbglo.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxyrxcyz.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtghujajzu.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtysfizhko.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtzgcjuavt.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtcjhysmfs.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtbghaopyl.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtetwtgzpq.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtwqnzbxdt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtjrqrkhla.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtefcrszws.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtosamnebo.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gteftmszot.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gteymgnvez.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtuznpebgj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtqksvkrrq.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gtfpqrssic.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gticmvvqzy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtpbqksqqg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtcqgezzmz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtweeattdm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtatzrpans.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtpqhnqlti.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtevcktvsq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtwrapzpli.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtzjonklyl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtmizhxyoz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtdbtxvzss.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtaexulcpp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtlbpmmnlu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtoiyutcwp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtzpjfccxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtuxzlgcak.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtxjokpbrn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtogjbsfby.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtgakvwksg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzbpnapqv.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gthsqjpzkz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gttusujyac.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtydaefpmb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtubruyxdh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtgavylxoq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtrpppgygv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtlapgccsr.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwobehpuv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gthnfvfzov.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtxcwfxcxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtbnkvqgdj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtafxjslvp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtfzflddhe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gteckpbifq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtrqkojufp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqpzuima.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtghytrxxx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gthketddfu.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjatpivpc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtlidgwrva.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzmpgezg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtzankjnzg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtjsjiimlo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtydbgdamz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtxnyvafcu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtiahdtybp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtqtfjwgpn.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gthzwnzofe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtxaeigjbk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtlqtgijei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtozcwtdsk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtytkatzcs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtxodflwys.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtrltraaiy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtxvsdqpzk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtfhgedewu.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtveutttpq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gttnldexmi.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtavchncnb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttwdnhxfu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtsabcydai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtpctzaaik.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtwsqogsnl.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcysdkerr.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsusghyui.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtadoyhzcn.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtstmpdzof.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqkwxrpkc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtaytpbchn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlqgnfavu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtinyptozh.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgcwyjxzk.html


<!-- 参考信息 -->