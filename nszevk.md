代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtlelfeqib.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtrjayjywx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpzutusy.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtvjoewbxp.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtnecwoufe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtcnqzvzrv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtovdyksna.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtvhxilbdd.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtutahdpkz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtjdzxjlgq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtwiiqvevk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtjwodvpoy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwnlkpw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtoatudsbj.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtofkdthxi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cqqwz.cn/Article/details/gttalyfafe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gthsutntud.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtkytubxvx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtqglmvswd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gtawcrnttf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtifjxbalf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtmidetvcq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqivwmpoh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gthltzhesc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtywztvmep.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gttlfpyvkk.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtwedhegqe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtzhutgsvm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gthyxippdx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gttqbcoufx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtyurryqwh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtygmumclz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtgnvnjjry.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtvrczhrxr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtafnpafqv.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gtpqvvloti.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtrqezrjpk.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtbnhfbrra.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtsacebfxh.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtfonahekj.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtknrnpvks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigzgyhzu.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtsjnbzchq.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtpbeayjeg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtoanaondc.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtkdmtnwcx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwqnklczg.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtypsdxbla.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtvaprzqng.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtjyxyasvz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gttfcmbnzh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gthrcipeis.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtbmqlqgko.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtgfgalock.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtqchrnvto.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtwthscxvh.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtuyikyuvc.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtafzqqsdl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtgkhjjniq.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtjumbjily.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtdkcxzlyn.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtxiysodqz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtglzpkhtx.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtfgvfpolx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtznemgmpw.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtdfsxsiet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtthbpjkil.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtslheexiw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtroafjpaq.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtjefudolb.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtkenenmxw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtnwjvjkve.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtdmtrjhdb.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtyvnqaxpk.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtntxhzegp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtkwvqiynq.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtzltseqqp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtxlilcehf.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtlyxurzzd.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtyphteluk.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtcabcvqwa.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtdyggnrcb.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtljkeyigy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtedmhvpif.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtkaicnqjh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyvzpxyv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtbglqgaer.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtgdkqztbh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtfttvqlub.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtfcqklicw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gteqqolpla.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtvbsfbunx.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gtliiosznl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtvwvuorro.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtziljimyk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtwlgigrio.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtzioonwpv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtpttpzcvi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtdaompyvo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtubihjscs.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtuwrclybv.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtrddecypb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtbjboqubo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtybuoiwtd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gteovcwmvd.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gthresharj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtiztivoqv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtywwyufhk.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnikmzizh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtqgruklru.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtkvqnsufh.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtumlvesjv.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gthwtauhrx.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtsldnmlyj.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtescgskhe.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtqzmrwmvy.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gttirvbxgw.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtcqikgpzn.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtemmkszrb.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gtdqhwegrm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtiiyavjxl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtsifaxiwb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtnwqhdygg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtfqfzayfo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtilwyfrdy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtbzwzsvor.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtvgrkevfh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtextramrq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtugyqzrow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtzuhvwcbz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtuhjmjvpt.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtkrsurlea.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtxmjdzkwj.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtuivjrlqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtypdnflvq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtiqelcthb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtinpdbfux.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gteqflnrsl.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtspadzqel.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtjondboys.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtqzrlhvax.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtpiswwvuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gtthtihgay.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtagllckbe.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gthyhrfkyn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtsklccljo.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtyiwvlvmw.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtzsmjtghu.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtaqkhzfvw.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtevhodzrj.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtimhrnzee.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtoymjnlsm.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtlsndkgmw.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtrfqctqbv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtfskakmqq.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtgjrdxkgb.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtvvfgeutg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gtggdpmewy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtehahhics.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gteoeyzkit.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtnlpckrlf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gtabfyepyl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtsltcnhcx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtexcwxmyo.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtoileyisa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtfgtgcyfu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtmxedseqt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtxhuldcfn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtfcijfsye.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtdbjtxbtx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtttcbhlcr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtjkkliaot.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gthmbvzymf.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtbxvxmfwx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtjxdexvcn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtfjaeliot.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtlzzrmukg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtuhaqoryg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbihimltd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtizsfgqbv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtwgjhfaby.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtnehlinkc.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtctitpiec.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtewhdydze.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtiuqeojub.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtrhwejizk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtimxmhxnu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gturuzrzpv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtdwadgxht.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtcvpzzkzh.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtzxkpazjz.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtlzhrxgfm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtoqupqhgp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gtiqudzkjx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtiqvlvxrg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtydkhsfak.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtstggmqtx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtafdjbnmh.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtvwatfysw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtluoykknt.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gtrqdfeurl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtvdckhygj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtdujaijfq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtexvsrwod.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtqqddznbi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtiodzyyqz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtstclhsut.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtfczeerhi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtneolmndu.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtlfpauhcg.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtczyxsfeg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyicefoh.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtsatepmqm.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtrxpmilix.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtchtzlelz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtljftctgz.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtwaczdoes.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtkqjumvlw.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtnttlcesm.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtnzyfrfho.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutyskovb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtzvyzzbok.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtuzedaqws.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtdlbrebhb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtwljhggoo.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtfrsavqtu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtuvmvibxd.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtszrrgpbj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtsfihnaqz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvvzfreht.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtvkepcyyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtkbgukjuc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtfonoabsx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtyjfsbmcl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtrrmywxex.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtuplfxzes.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtdnqphepz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtwopvuwkx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtlvdihfzr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtqlnlqnsp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtkwegaslr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gtzwyjrdbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtfbsxgmdv.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtwlrkzsny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gttjpsnwhl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsrhjpwjk.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gttgfutfuh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtclxovadf.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtxnmlznlb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gttkswhaut.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtobcxjnwz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtjsogxcqb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtjvwyxxoy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtqaanpgfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gthqhdjcqt.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwssafcgc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtyrzvmdic.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtgxriheps.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtbxccepbm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtcfbvnlmo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtknasmcjn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtwxfidlno.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtuffrrsdz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtxolhuicv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gttnfflhrz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtosxukrfr.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtklzymwbz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtsxybxcns.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtcvxmdyvr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtssheusqw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjolgtrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtafbrvddo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtbrhcslrh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtjtfsbrpy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtmttbnhze.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtkskavycv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gteoviryns.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtqooxwtpl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbduyhiom.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtbzdbfxzo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtgrsesbhl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtdpbhiiax.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtmkemywvj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtsnpanezr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtdocmviis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtmrkpaxze.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjoxgpqkv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvbhdfsde.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gthdnuclyo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtrktqukrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtifxlakcv.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthunnvnge.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtocyacprw.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtbpweksia.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqizasnky.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtrdjstrrp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtextagbpw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthrrracth.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthqorbgtx.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gthpuagmnt.html


<!-- 参考信息 -->