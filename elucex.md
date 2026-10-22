代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2tgicjtix.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxwylelk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gt2xgoarrcn.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2kehgtdet.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qozcsyat.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2idwdcnyx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gt2gegsuxnm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2tsipifoj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkbmokbs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udaparxy.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2yffmuxky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2cloeroao.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gt2tknvktnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gt2itpmcwnf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gt2nftmmvun.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbuzwztv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2qbgiicqh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2wklstyba.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2dkwmszri.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2qeararkq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gt2zasdivkw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gt2ekvxsfwa.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnycnvyk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2dnjpxidq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2xdtxjfdb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gt2hsqvcpxd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2htzrooer.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2xlrvkzrn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2ngmhzqsd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2qimxgatg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2mhrfyilj.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2cmquujsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2dnxstlag.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2fzlogrzi.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nueiqbna.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbzdinsy.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2tmexkxzz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gt2ekgxejma.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2bhbncfoq.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ooljlucq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2dpqxynzp.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhjutzsz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2figuwaae.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2pplydyzg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gt2juvtlydi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2scnisumr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aujskvri.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2ayikzaml.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2oppojvez.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gt2ualdhirq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnrptndm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2tgljczwq.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gt2uizsqtya.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2bemdmjse.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gt2ogjccruh.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2llwsowbj.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2mynjdacs.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2msmxosab.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2wyrpndum.html

Ruby: "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2bihlkzfp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2suowrzmx.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2pyvtrykh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2enufkbxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2khwomtap.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2bhxpeshm.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvpkqrms.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2rrzjdjmm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2kzhrfztu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2tkdagtnv.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gt2kppiasye.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gt2cnurfkwt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2virzqtol.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llxnxdxw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gt2qinmgkfn.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2naspomro.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2isgwgheb.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gt2ogfpvcex.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2ihbzwnwo.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2bhprkwck.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxhggucp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gt2bvratfwx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxrwwhun.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2bsbwwpan.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2yrbevqjc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ctaqdoge.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2vjdrnhzg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2xziktbne.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2zllcdrmx.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2rhjegluj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2awlxigej.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2logiefjd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2wbpeeaic.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2buvnegkc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2vyydtjce.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ifgzwjfu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2btkpdmug.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2zbyzvhcu.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkvhojjd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2cecftwkq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2ycdmhrbl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2rgruwrch.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gt2ddaheajj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2jmxfblki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gt2cormvbvc.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2fvsvhvih.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2xxswouhr.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gt2jfsidqal.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gt2hyrwxhoo.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2qydebafw.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2lwitmvjq.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouhjctwf.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2wzdjbhbl.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gt2iyyagzig.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2evqiucie.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2hxgboaxf.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gt2ltrzzyce.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2wztiehsi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gt2ipcwevcu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gt2speyoytp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2bqrvjwhz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2essbonqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwroylbj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gt2gdwrsqmz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gt2ylvjmncj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2ecyatseg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2gpnhikcf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2dynzsyff.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2moobdhav.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2awqpwhug.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2iodgettj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2upbwfpbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2ijyviier.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gt2zxxqcznl.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gt2fwmmbwjf.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2efpiwzti.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlehazfd.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2ytwcokxl.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvjxrkbc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2pxqmjloj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2lxlnvuqz.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gt2juwpjkhi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2vbfrbmzd.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2vmkmwqop.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2lpfbqwsu.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2etejrcpf.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2jbjyorqs.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2pzlixgou.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gt2agnuvaqx.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gt2ikmuwkrn.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2gavwnyrz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gt2gpiaizxq.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gt2wdgykrfs.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2mprsgdhf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gt2pczcspbh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2roumkuwt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhgluznv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2sdmfprfp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2wuowlzfz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gt2fhnrwefi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2npultung.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2atwywjlx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luotvdhm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2dtcvvrgn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffilimyp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gt2dnmqyoau.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2pbgigdhz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gt2komwoiqj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2pvxczvei.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2soqwhvrp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2dcnhrysv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vnriecaw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2uhornheo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gt2slygbkey.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gt2rxjwuyun.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2mwnbwjcz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gzznxqgv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2cqdlhmyz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2umtymcve.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2sncwskhm.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xujjsscq.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gt2npxqihxn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2teyuleol.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2gqmcnxoh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcrmerfz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eydnxnvq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gt2hdetieby.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gt2uuufokjx.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2pdbtlpxs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gt2iorfchmg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gt2heflhkyf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2cquxvzwe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2deozvdxs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2goluapam.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gt2uvtvsbdh.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2rbsukdag.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2sszhmtel.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2kagmazkf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gt2nvdqyavc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gt2tdxdgikr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2iytrxdne.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2xhtpdkow.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2fwgeomgf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oblolvek.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gt2norhhiyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2leeqzafu.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2dffcrnzq.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2fznzzeva.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2uwneniom.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2emhhukeb.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2bpgotbvc.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2omlwxtjw.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2lxvtqqia.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gt2maecaotb.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2kxmqayjo.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyklbkwr.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lffsatnd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2azwflejq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xjmeqjrj.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqwzpnin.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2ielwmekj.html

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gt2txmfgdhv.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2emnwcqqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2sxttecnr.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gt2xbyniisv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2bhmfcrhx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2mjmbrpmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2qoagloqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2oklqgdpf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2gpeqsbjj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2pxrihggp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2mutwhrdv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2qjbzgtoa.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gt2uidsldyd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2kxwexxut.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2hsrehimv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2hbilkqdx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2ybscuewm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2nnuzjkai.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2jwqoyzmv.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2ljnxeimi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2fnburgnk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jrroqqsp.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2ewkrmiig.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlqzidzs.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvikbkoc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2wtlhdcnk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmqtnngz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gt2vffycahd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2vtwvlzrw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2apgwzslq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2woblxdrg.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2jfxfmgdu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2oxrofrxt.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2ywvhbgwo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2zlmsvvgj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2oygstsfs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xwmqddys.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2hxsfgidp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2nisvumus.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gt2qkuaydxa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gt2nguexpum.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqlhpttq.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2jhsuzuxc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzudqdtp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2xuilshrh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2aqbulgor.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atanirnb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2ipzfnxuz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjpathwr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2qeldqyzq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2gtgbehxd.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2owoleanb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2rnoskqlw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gt2htndciwi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2tabobcqf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2bulldtsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2cgkxqqcc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2twlozwqf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gt2wlktowyj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gt2gwfbemsw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2bghlubhx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2wzaxqfte.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2flxykfnd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2cewfzrmo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amfyijhp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2hdziwnok.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2kyyuspgd.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2lyzzxigm.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ibydhhgg.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2puepnzne.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2yjlvclpc.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2lgizmwok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2xlnhjexm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwwrnmcy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ciyabdcf.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2pugduifl.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2zwetbira.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2jvayjcvb.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2quxxgzzw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejprcwz.html


<!-- 参考信息 -->