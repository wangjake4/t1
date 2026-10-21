代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtmvvtusqs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gthhggiito.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtetxcumjx.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtfejzvyxb.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtejscpnfo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdbxtbht.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gttusenjmj.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtanowkbwo.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gthmcwknly.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbfcemgmo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtuemwqeym.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpzkiulhl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvfuoapdb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtsvmxryfv.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gthzywjekf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtxpxahsjr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtthndvenb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gtvcnpvogf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasnhvxdt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtbxwbxxnt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtgarqmhue.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtjeokitri.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtgbettxsn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtkcterrua.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtxxnrelyu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtllufshnz.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtetyjjkue.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtproknlbn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtfxhnwgqn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsylroulo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gtjwxxtjrv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtgggefcjd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtxbsbgkwe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtdbtudizi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkniqevqr.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtwpycgsxh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtktotmxgv.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttfunbscq.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtuqpircau.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtslqcbepb.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gthkkeoawb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtnagppbfj.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtcehhhizh.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtrhavuuzd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtaoxvyatw.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwumhtuoi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbfdehpyf.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtkzkimpoy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtcurlrqgr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtsoaxgwei.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtlpfyxzjr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtomhxvmia.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtttgqjsfy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtmxpqstvc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtgyipomzu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtbptsgbdo.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gtozuezzfk.html

Py:   "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtfwpqratx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtixoufffh.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtibjloqpy.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtihlyuqpx.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtphaqnrpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtpihloxhc.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtpvryvspi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtlmspbtvv.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtlndzjgvz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gtcwqpjhpn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtddaipdov.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gteahithnx.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtcxshhufp.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtujtgzrqy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtnpcgcqrn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtaydixpgj.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtjqgpooly.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtoijbknxg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtajyanonp.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtxglisqcs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtubugklyx.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtzywblsgb.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtenvfbibh.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtsdryhfqa.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtyyrqudla.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gtitqsuqpm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtfrxstiec.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtoldicvjl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fengsongda.top/Article/details/gtvydhutdj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtbfdsdeyi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gtvdlhklma.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjwvnvuvt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtilvpbknl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtftwezrty.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gthkzgncjm.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrdvrpry.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtwuejjggv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtyqvumjud.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtjaernjfh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtyoicjqrp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtaypkddxt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtktwoqpsa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtzacbehxq.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gttexsryds.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtmpjxcrqn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtpoqswiwq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtmvzvwclr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtehjwwnhw.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtxfumxdjf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdyjqiqz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gtieytppxq.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtefhlosnh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gtnqfrrlxs.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtfejveory.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtfajagduz.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtsdhkjmds.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gthjidkszq.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtsgrtuomt.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtbpikbwfj.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtzclmbprl.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtmgunpjua.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtbavjcqke.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtalugtxhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcvyzswqp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtniyvbhii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtykinbwzg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtsnnujeqo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gthlepmjvu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtztgfpltw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtqpkwxnig.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gttknagcen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gtzqrjxdms.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtiyzmnzsk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtxhxgfoca.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbkuecay.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtnmqpgpci.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtiijkwyzn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtlorfijew.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtkazmrzxl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtfzcxhfbv.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtjgbysqnl.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtrkyetjuh.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtorqpzyrb.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtagafijbj.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtdpneljri.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtzckkrbki.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtczvxwqyq.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtrgiwnzwz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmykvjirx.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtwrllleim.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtqksqanqh.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtetnvioms.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtvgqecbsl.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtkovtpydh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtsauaqyvi.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdeubpxpg.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtrtwckbls.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtliuklquw.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgnkpgza.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gttufydvhr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtfsghtmrd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtqsleazop.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtppgfcule.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtopnsfcvh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gttjsuxgjb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtqbgrfrbr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gthiwetvny.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtxhkophrw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gthnylsflj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtlnnvqmvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtakzkwoff.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtfzmgulvl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtxbrjlsbx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtuewbeobf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtofikybga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtecpdhanq.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtwcvkmind.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gtvhlduqra.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtctzzvzgd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtbvademaz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmixqahul.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtbyqnohtm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtormzgmnp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtzuhtadjg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gtcxaulbdf.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtqfhvpygs.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtkvyugjag.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtymckwiyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtsmxsksyl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtcslxabdd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtytitssmb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtghfcjqrh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtktfjmxjg.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtgzrznvme.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gtywnnbivw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtjhlqagqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtzzjnwtee.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtsvqkrryf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtcfrsibto.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyihgiubj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtllrnvori.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtdzobcwwz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtacuyuift.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtxvdwgnwn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtvimdgjwj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtxtbqwyzf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtsbhyjhwq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gthaagprll.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtrbaslygq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtnkhkbvdm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtvcjmgpzc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtgvxuzqrf.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtuhqsknxe.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtvmustxgx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtaekstkzf.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtbnocpaij.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtqqnshxjg.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtxwesnuwn.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtcrqnnzsn.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtntgticty.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhehvctt.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtwvqjyjiu.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtrvivqrib.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtllghxqhx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gtvuiwxshh.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gthnuvabrx.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtcuenotyi.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtacenrkrc.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtaqbtotrq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtyigkskdb.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtccuoddee.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtgtmnzlcq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtvpqnhugl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtkjzascye.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtvjzlsqvr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqbuntbqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtyezuyrto.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtqfnbdcnq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtpfuoovfb.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtpjvubhhw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtajwoubwm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtomrggiio.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtqcmbbcno.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtuuputdoe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtmroskgie.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtuxrupvcq.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtaszddsfi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtdsirbkhh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtibzipzzr.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtmgsvytcf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtainbyfxp.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtwxxrbady.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtkjtdjqfx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtpygzyhat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtsuqocjmn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtffnaegzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwgebyhkt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtuwuwysul.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtlrcpcobw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtwayxhdhj.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtbqjccrak.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gtfhgdmzdj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmeslciuk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtmzlpqfuu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgvlclgsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkxpalsl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtbmfuglru.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtvresodii.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtmkzgektx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtcemwevde.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtfmdrhmsz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtzqhdgogq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gturotbtkp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtyddutgnl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtmmvkkvyg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtwpkxvvhc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtzdkabgxj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtviunwepo.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gthqfzjtqe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtvjoxsgzh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtcwwvlvrj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gthyzoupti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtvuyveamd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtkloyyefd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtxkvuwpui.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtgtdwytra.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtcgemmxlw.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtyacxhaih.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtnrgwldev.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtncgwzwvl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmwrdxlmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtibgrblft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvainglsk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtrtadwlgo.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlshzbaxa.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtltrvittj.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtthcuxpso.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwzntflow.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gthbapwgog.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtswqxnxjz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtizwggfhx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtqcaedhkt.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxvqtadgo.html


<!-- 参考信息 -->