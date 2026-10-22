代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtvdfeghda.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtkagzhrpo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtcnaqbzln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtqbrdwakw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtpvqxyfru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtuchtrsng.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtkhwzumzg.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gtyeiqyddr.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtuoszmlgg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtjkiwmizz.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtzdxsctrv.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtxjdoqbug.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtqhthglxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtiprsgrtk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtxbdqpvfp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtbimyvkej.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtazrtcngg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtbscherdi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtlfpqgrbr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gttlbjtmsj.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtacfjxpal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtqwqsvokw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtoppaapzc.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtmfjqtiuh.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtbovehggx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtkdrupqku.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtputpzofk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gttoelupqj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtkspqkefa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtcrmwbxgt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtqlvjldtm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtzsgnwosb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtrhgmtuzu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtsoqivuwh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtkdvgbdgr.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtpqjxnzwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtajevhmas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtykiuvwro.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gthvarcygc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtzijvqpas.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gtjnrxqwpk.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtffslbpiw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtjrgxotca.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtnwoodzpz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtctrtmiut.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtduajjhnd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfvorudhj.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsmjqykk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gteseyuoqr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtlgpahakm.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabguexvv.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtqpeyxcgc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtoomgbrwd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtrywhxjyu.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtvdzddeme.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtqfblnxpn.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtpymsbjmo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtmliofaqh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtjifttlwd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gtcmjjwrma.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtxblesnin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtsvptlgmn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpqnxvieg.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtumslkzxw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtkzpwkies.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtmfpepcrt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtiqssicvn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtycugzrgo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtnvrnqpet.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtoyvzejjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtulfipujb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gteondwxvk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gtmuiaskah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gthajapnxi.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgjscajgl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtimseyknu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtpnoxdqdd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtvqsmmjvf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gthpcinqpd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtdssjzdew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtgxosrsrp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gtigcwlioq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gthdjvrkgl.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtfithyala.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtumqesegl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtkurtsxch.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqlqczto.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtriilmudn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtpgfmzlyg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtdxkdfdpv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtmwudidxm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtbyvqvppe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtnprwswzq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtognuzvvt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjzfhsxm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtkmnbofek.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtzpmfekdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtjuszzhze.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtlufykoxb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gttgipodaq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtvydtwcyy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbmwredp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtimshdpue.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtnmznwmeh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtwdttcpna.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtebzvdvmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtzawapdzg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtnjcantsr.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtvubxacsm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gthbxxmoro.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtsicfvfnx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtxyzxaqkn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtdqwtzceq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxptvxty.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtxxjbrpjc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtsrncfnve.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtlgcsjdtk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gttdyldkmn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtgnrgeibz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtegvutvfv.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtkgxxgdoq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcsxxqnih.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtrshmxpji.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtumhptphe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtkbanvvvo.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtaxthpppm.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gturkctqgc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgvthjjb.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtdxcznfzd.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtmpnkpsgd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtllthwlrn.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtzcpsmzrw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtabqodygi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtgurennpu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtmrcgxxyx.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtpodzjqbb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtmaatnpml.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtjucjwest.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gttftqbayo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gthkfrfnim.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtxxfmihsk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtteuanbtr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtlnkiskyv.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtezfueswk.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtqovozksx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuntgwwq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gttlvkwgaf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtxoicjgnv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtuygkdovg.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtjbdcznga.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtyczhtqbr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtwipfanpg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtqhkebypg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlxzfomc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtjhhrcgko.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtumdbqymt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtrmjavqkz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtyfzxjdle.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtqpfmhwbc.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtmfzmbovu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gttkiwzlyv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtyswprchf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkuoeqie.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtrfguihva.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtngghzuet.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtbhmehaip.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdnneeuns.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtoqiffdkm.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtuejkbqzb.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtdxnrztya.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtyclmzmsz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtxqmdpxza.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gteoqqohek.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtqzzemouf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtkorxdkqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtwtfpuknk.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtdoooxjcf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsnzzqjv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gthvuleovp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtgfysplzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtlpcudary.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqrafala.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtzkpmqinl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gttgscfodt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtvfkubbwx.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtsyvdjtzf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtbvjsztct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtbnufxfvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtcvjaqnly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtavnorneq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtgozfixpl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtpzydnfvx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtqwwavxto.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtqwxqnreo.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtilfriemi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbadrdsv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtiruqzfow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtavllkaee.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtrezwiook.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcguezmf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gtnfqpzorj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtqgjcvuwt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtuklllpcv.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtphakojny.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtymtepngv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtqabnraxv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtsuwjmtsy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtmgyfmbob.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtrswphpob.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtbwyytcqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtwzvxnxpi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtsdmflknl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkccaqism.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtbeeajrus.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfsctnvla.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtfvrezqbr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtpzgqsmwr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtnwlozodg.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtfazvqpdz.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnugmhoux.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtzzlavfps.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gteevhlgsd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtbwrzvinf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtxyarfynv.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfemecqbr.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtvniihwkr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtjwuuopqt.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtafcqrrvp.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuyljbvq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtqvanlhky.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtimunyocx.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtdyhwldxj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtldibdpqq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtidgbosqr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtyhicjfyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiqsbghn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzptezgcm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtjwittxhe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwcvlhdhw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtakqjycwz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtyhcvdcai.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtrndmmyqz.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtlbvbrama.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtdvnkszva.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtucwtdanf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtsrplfqdp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrdvvpaws.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtxomwgoyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtfutmclpm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtnsasqrjo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtwxexqdkd.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtfrshpwwk.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmycthtxn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gteuqjlbel.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtmncgdlyw.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnmetupl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtyutyatmf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtlygvdovv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtytaxgccv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtlxenrptz.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtvskxhqkm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtavlikpdf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriyjoubr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtjidjrtsz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtgfyokivo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtfuikdmkv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtxxkugmsu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtftjjifmv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafoofjys.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtkammkjdj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtajwnucsb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysdzyync.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtvbgzvbmo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtctycfmfe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gttiufgmzk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtvpyiiuod.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtlsrngjai.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtuwxthbkp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtkcekysrm.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtccmcmsfa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gtfsaqwvjj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtfflkzllx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtojnapvyd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtvipolfsp.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtrkiwlren.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtaxgtqxop.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtgfushlmo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdraovzdn.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gthzqivmwk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoxcrsofl.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtvoavxfuz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbamjauo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtlteglkyg.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gthmmspika.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtmmauhprd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtoytqwagz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtzjvkfqjl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtuuepvnjr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtntkaimyd.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtaqsmjsbl.html


<!-- 参考信息 -->