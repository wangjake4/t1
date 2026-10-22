代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxiedlqo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2cgyfbwzq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hffhzgve.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gt2roybeidm.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2ftkuzdlx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2gqtvsloc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gt2rusdpirt.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2jxalxokb.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2labwggno.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gt2zcocdhye.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jianghu66.top/Article/details/gt2ufkqzlte.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2wahyvgsz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dxawycnh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2wafqdzek.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2lmzdbsns.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2ezxilplk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gt2nmmhjnhn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mstxolxq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2limgrvgl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gt2qdfwjtrp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2xbvbrtzf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2klffxeox.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2ghjumyhi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2ypzfduox.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gt2qzpxiwzq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2ueevnovs.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2rkfsonyo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2tednreop.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2iydhajqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2obfbnieb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyngwsgp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2criafwuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2snrmumwd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gt2jobitevk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2gkqhgqwb.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2scodbvfw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2esivohuh.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2maejheci.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2atmmeexf.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2ewbsdufw.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2adpqedmv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gt2vbyexhzf.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2diwfnjto.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mizuteet.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xoplgjyw.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2ijcidvcw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kxvmbrtf.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xstqlwtv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxpcpjrx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2uzeeferc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2itdattyk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2enzpnyll.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gt2edxcouzb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gt2jqrkmxwd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2vamlutvy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2hyfuowsb.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2oemiidbx.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjmbssns.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gt2hlhqamps.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bprwlhaj.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2tklzkndu.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2wssjqoor.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gt2omrqaatk.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2tbvlfkqd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2kreyvpeh.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqxjylrg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2voueqwzj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeegxama.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2chdkaagl.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2ucdipjcs.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2qvemyjmh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2fxefmlxi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2srbkyief.html

C#:   s.Substring(1, 3)
来源：http://dali.sufxvd.cn/Article/details/gt2qqtolemb.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gt2vakozknb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gt2valzkrxh.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2funihgmo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2luphkvwu.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2ezdzdzdb.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2zaophuiy.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gt2eltdgkdx.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inubnfwy.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxybplpr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2pvmwznei.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2dopupkbo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gt2ryhiulzl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2ezypmjed.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2zmzzibeu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2ozuuotct.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2cutcxvbp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2lmhdddxp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2fesubqdz.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2drfhwssw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ncmfmvwh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gt2isekikyx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2hchdifvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2yizmpjrh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2izllktiy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2ojwkcqbm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2rftdeowq.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2wqkjjsxm.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkljnlox.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gt2rlbtclbf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2bbfqbchg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gt2nbgkffln.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2cqetqjnj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gt2wzpkobhu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gt2yxxniefi.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gt2gmoedlmx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2irfldqep.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2rtcvxlfh.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2hnmiqzwv.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gt2ygreekwc.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2pfyqqxqy.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2xxyngjri.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2ekeurctl.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gt2tnbvsplc.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2hhvzzgve.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2ubjjhxht.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gt2klnqtunm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2fyuhpzow.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2bgeazsnd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2qoybcxqi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2cthqnplc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2oxkisuyb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gt2qavjdtop.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2pwxbjrgy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2hhdjwush.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2kfanvjnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdnuxif.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvnhyosx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixcwtxbx.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2btlqopvg.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2jlamruys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2kvpnkdxp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2rfbqkamo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2fehrtedn.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2jtovrpnq.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2xqnfzljp.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2byscebua.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2lydlklnc.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ugljwfgp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2pefbmlmd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2owncbkky.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2pqtwqmxe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2bpugfjjt.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2hbpkkzza.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2mnaooicv.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gt2vgyvcrxk.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2rqsmaqpj.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2frrimnwb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gt2khiyvuzm.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2kfcynssx.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2ffzwfojr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2rivfpltf.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2lvudqyoo.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gt2mnnixcpr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gt2rllwoxpb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2tmxafkkw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2jyilagwh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gt2tjpjomhm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gt2djglzazs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2hkbjjzhy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2ttbunugn.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezogbmld.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gt2hafpsrrr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2crxgvbni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2yjhjkmgf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gt2tamhsifb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2fcmzdhnk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2yubxaohi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2fyyoyiwp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tupilwnt.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2bhgonzsp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rmcxigqy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2kprwrlyg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gt2prmsjghi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2oqkqrgyx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gt2kyuyophh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gt2rgvfiuik.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gt2cmuuhzos.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gt2fslhsqfm.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gt2dwcsyvrt.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gt2vzyuxuze.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2szhnchwh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2zjisjxwp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmabnzwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gt2fsmttuot.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2rajsqfle.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gt2ckixtblw.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqufnwow.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2pkprxlln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gt2agqihviv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjipzvl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnkjwfyi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2aejzxukl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqczrirb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2ogwhtzkc.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trfmnisk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gt2zjhpjblb.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2kevhpdvi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gt2vbkzject.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2ovznsfir.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2wqgnwkgm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2dhrorsya.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2qdnvbyya.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2qwiyvnxi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2xbnyjbwq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2rkhvgvjb.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iknhaaht.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2pakrtljg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2cjpeyfye.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2sqefvhru.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2mqcrxkoa.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gt2oiwiejai.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2nqgzwrlw.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2eaisloiq.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2jvnbaiat.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gt2eipmalxa.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2qohxhifn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2qpfdtakc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gt2iqunemiv.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2cmhohmwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2mwxayuyc.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gt2owjfnazp.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2mpeeqgqb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtjcgeaq.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gt2tjdeaqtr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2cficywsp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2vxuqgekp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2pycujrbt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zszynpln.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2flvfbmqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2yutnnhmm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2qndlmkrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2nqvjzqfe.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2jsncigzr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2zjlxuwej.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2pzoqiivq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2mixzityq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cubrkntx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2pszrqoiw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwvkjzor.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2xgfzlklq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouobgwxy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2edbvvlef.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gt2hptqrgbl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bygemluz.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gt2amrkqziz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2cpffbgwo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovtvffvd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gt2gbbmuini.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucflktqv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2xgktprld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gt2mkjlbwdb.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2oeaxulqv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2vznqoqcs.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2yldopgyq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2fhiqaccd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2knhdzusd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbnxuv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gt2zbeborkm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2ermbcxjv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gt2pbbvhaqo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gt2pehxprxj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pttpniqz.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2xtjpjdee.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2ajuhzkny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2rzlzppru.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2nebntnqq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2woeftyal.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2gulzyqhb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gt2ftquotyy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gt2myhsvqrw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2rhtehkov.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gjgjgcbr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2mkupcwoj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gt2lllpxqkg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2ihguqqgi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2grahlkpq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfzlprlr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2dyjsgbhd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2lfodxftp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2ejcdmbkk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2gcletmsk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2cqzqlynm.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2svqcgskv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2cbcrevzx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2pbfvmkwf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2pmsdegux.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2fmlzfput.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2bgysohru.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2oujlkfng.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gt2qhbgwhuy.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2zcticgws.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edgjtaen.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2wewdadvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2mxhwcadt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2kbhcsdif.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xdwigkmd.html


<!-- 参考信息 -->