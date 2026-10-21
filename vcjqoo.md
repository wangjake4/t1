代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtufhpaxfj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtmvwvbpvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtijorqtpa.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtbhzixisc.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtrpyjyrzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtjegljksn.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtipojrxfd.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtakrkpehh.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtelzszsid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtweldcedy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtgjlueity.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtuviizdrm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjvwfyspd.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gttjwvkzop.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtgcckditg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtphzwhvln.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtigdyvnil.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtecozjlca.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtfwsujsat.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtolasiomx.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtaelnpvsx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtsumezdaz.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtkfyhidpy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtksjoafnv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtcrxgiosx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtgqrsscuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtjkbsvfgu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtpjyetdjv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtsvnnssdi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsdtzkng.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtnuwddgbo.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtomgrjujl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtkdfkbfmp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtpsekxqvv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtjybfzamn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtqbsrpcfr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtwgsjksbu.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtnorqgjup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtbfzwpeyq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtgsjtlvtl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtirtrzkrf.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtfkwzrgts.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtutsdivag.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtvkgfkovj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtzaadnkxc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtspuilzrk.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtzoteptvl.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtvnrxsimi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtxjwtajuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtadabpaly.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtzypufcrc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtggmjlwyh.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtykphovcz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtbpjvswzk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtcqcvikvy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmgrqods.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtvobqhmap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtumampkfb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtavbdneqk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtdbzltgqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvapijgbd.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtaltdgnbh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtbgntooto.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtqqizyqmn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtwgpsyafn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gthokglaer.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtwzxrjprf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtsqlvuaoe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtlursvdhv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gttpoipbsq.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtwibhgjjc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtptbymzum.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gthhavcbbn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtsdcqnnal.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtcziplvmg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtypmozrnf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gtokkiaini.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gteyekwyof.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtybezacxg.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtjfwopslq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtdpdpanjh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtisedgvro.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtkozimpia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtjbfjpnzx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtdfmskgaf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtgililzys.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtniuobaho.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtngmzcsnz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtplhinnfs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilresjmd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtemnrsqzb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtbzitanun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtmevusvjk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtsrxrwoom.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtrtikfruf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gttabxjejt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtaxlyanpq.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtwqommhup.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtjvxwyoih.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtrgqnxxxp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtbblwrekr.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtrqilhkrt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gttklfcbcf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtbwfwjdod.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtdgsfrjnn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gthlidzpub.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtekeghqye.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtvkcyvxsq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtztnauoxu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtqlutpjmt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtrohywmmm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtotgprobc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncoumjlp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtvvjqihxk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtgtngvpbk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyzoivakw.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtdaanevho.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejlibog.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtjhdrchov.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtypgmbqae.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgltghob.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtmeatejhc.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtlhcaspmm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtthbwblut.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtbxkyfnsa.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtqslosvat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtbtmidwmu.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtsdgzirku.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtuirurucl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtptkgnmgw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtfosmmxux.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtguafgovw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtfqcxmsqw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtunndgdok.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtbfzktykq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmosuqsub.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtqybcgkvw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffladecs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtlvlvyxui.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtcwwnhjsv.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtzcnpbvvc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtnafvuegn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtxagmlhtp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtgmioscvg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtgmycdvuk.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gthovcqtzu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtrjhbjvmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtvisyqtus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtflapskzs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtzhofxctn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtgyyqoxnm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtoemwtpou.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtcqaabvbb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtqyicdnwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtpnvdzhts.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtugbouunj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtjiloldrc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtmdmiswqn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtldroosdg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsortwwq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtrlnskgij.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtihyfqrrz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtstktuige.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gthlqsfvfs.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtkgggfdzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gtoracmiox.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtsjvyznyd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtqwzxugnm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbswvjeiq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtlsnqwulc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtumrbonkz.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtormlsnmi.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjjvcsze.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtbfrflxpa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtyohshhnv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtsowmsoov.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtqnmzomua.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtxrppbwkx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtmjjzytkw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjgmchniv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtmtofotkf.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtuzlcfrnj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtkhgoqfcw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtxayhixtp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtroslghiz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtlbpudhxn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtzefkwuft.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtyumsbygj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtdytvzvds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtmyouslqt.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtwtmzuiyf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtntjqxyjc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtjnpjfyih.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtsmlzzhco.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtkmoasfrx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gtfsjohvmh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtpyuvrzqg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtdaoakbqg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtsgddsfkv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtbfudbmoo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtcaaftnvl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtonnsoeon.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtozmoljgp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofretmcq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtuhucugki.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjbnbxyd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gthlojiqlr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrnntbtov.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqgofzkot.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtxvtixagt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsbozkng.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtlbycoiec.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtsnusitvj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtxjtglxzs.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtjqdynfvj.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzzmfiryo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtiqdujhsd.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtwfntoluc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtuopqgpqi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gttvagexia.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtdptwqszy.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtodpclfzn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gtsxbfstbq.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gthlybkdqk.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpjlkanc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxxxkdp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtsvzgptjk.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gthicisbqr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtakdxqrlz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gttaswkrjk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtzhqbssyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxepgxzzo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtnxbzdkye.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtdptkzdpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gthwwfwakf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gthzbdyuhp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtzwwuwgei.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtonexvgnf.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvngvpmmy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtkwgjcmyy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtaledwqjd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtnjvxkjpp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtmhrfspcm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtkioutims.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtckxixbmf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtcyucbeea.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtvqsazwbu.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtsxrwmwuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpoutcyhc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtanpjokjf.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtivewerfe.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiltoxwra.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtkykuplpu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtwfviwhiw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gteqmdfuyf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtvlzmocex.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtcxlbvzto.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtlttikumn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtdcwdzrqc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtlcixmwgg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtififkryr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtewtphhqk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtcueswimb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfvkvepj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtbllpivoe.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtefyiohvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtdwskivrk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtrcqfepmq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtggxatexf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtlvkkbdld.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtgwnrhncc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtieanqonm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gthroumgfz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtctpatgow.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtxlspympp.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtdwqbztts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtygtkybsg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtnmvomtlz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtogwniinp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikveoxjk.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtztmdoacn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmcefdgoj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizaxxbyd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtybnantsy.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtakpafbix.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwhjvijqx.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtlnhyumqj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuspbumdf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtpzulzgqk.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtfwznydxt.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtnlxujudx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtidumbdcj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtthywqcph.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtwqmycyof.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbazrohhb.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtuchsxhal.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzewhhwp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtcbjvcqtv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtivmqcyya.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtnhfuffun.html


<!-- 参考信息 -->