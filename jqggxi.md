代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtpfnzbnpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtceeadncr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtmjhrrjma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gteoqknuxq.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtywdlwwea.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtrdvxytpr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtvrngzrwn.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtttbwjkzq.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtadnotkaz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtphwftfjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtjikymhsx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtpqlofgce.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtzfnnzbqe.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtsqfwugzv.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtehfsdqaw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtqlgrmatl.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtykdicqjx.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtontgplxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtpgenugrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtwuutulze.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtstqiyovs.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtcufblcau.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtnadzmnma.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtibyidosq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtnchrltbi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtuhppmmse.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtjiyratez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtlwsqdbss.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtowsjdsky.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gtxdzmroxr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtighmdhke.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtsjmqqvzs.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxijdmwrp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtpnkonslg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtuuusiwap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtlteekvdy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtpdyxdwhd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtfopjxbpc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtjawchhda.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtqepkonrw.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gttgjqvuip.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtqrxvwerp.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtkgahfgtl.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbzkwsypb.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtmzogjqgf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtlosqkrpf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtjzxgpwxw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtembzmbqe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtayoyfsno.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtqyfcdtjk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtjyvmwoag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtimsqjjhq.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtppmqbdrx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtqomzgasx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtezumsesc.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtgilpibjk.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtiqkykzau.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtcmtozzke.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtjnzzvump.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtxsbbblef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtjatyqler.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtxqutpkgv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtjdqybyub.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtidkgcqqe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtjgurwopl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtcfcfttiy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtsaixmvvq.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtvfdvjozj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtnvyvejhp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gttcmdmomc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtxgavzcuh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtsmcctobu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtndjbwzfr.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gteyrlqbyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gttaubmrnh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtjuhvfddr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkhetvycj.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtpxugzrnm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtguvigeis.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtuegwlhtp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnhohlak.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtqwshzhms.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtzupqtiry.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtmqoxwwgs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gthuyksmvd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtoigfxacc.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtcimivnpr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtigocjrbe.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtzhwyneqj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtbczktpkt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gthanjjbjw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtkskacpgu.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtzwjhpzdg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtqqwwumhs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtoeqqqkap.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtwrtlosiv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtdpqorqac.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtoafronsi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtgztxdisu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtidhzfyhs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtzbaxhaqg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtyaxucpbn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtiadaimpc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahocduxh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtulbwzacd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrzostxk.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtumedmewk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthctnexpa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtkztqvnqr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtefexfwzt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtzgtghjyv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtfxcbusyd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtypbjsjog.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtkmghvjgd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtrpadorgd.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtmqjhalti.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtlhfwmpkl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtlnauzqmn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gthzrmohkh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtafittfjl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtxljjuvty.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtzwinpuai.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtcfegssky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtaohlugzt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtsrwmxuod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtktycpsga.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtomgctvav.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gttxkqkywq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtatqpyrms.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtcosxqivb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gthwcsuyak.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gthzokqhrq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtcwtquatz.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyhvotmv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtneeghjmd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtvhfggdej.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtkqeasjxp.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtzgrohcoj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfozoinh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtxfpmdisc.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtaqfsevdh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtnvftumne.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtwbbcpgtd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtihgbcjfz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtdssxhdwo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtmhrarjoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtjotbuuwo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtnkrhjkcc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtvgappcuv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtuyhhptmf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gttnbkevwc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtinwgzcem.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtxvuwqaws.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtscyijunb.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwujhxaj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtnnqrikku.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtijhacydz.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhcsqran.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtwnpqaerk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtsarnvque.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtunbziydy.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtwrhlbjgf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtfjlsfkis.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtnbzzhemn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtnvmmjfav.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtwoisneei.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtpnyrsoij.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtloliikro.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtmtuacqek.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtwsjimeti.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtblzhrqow.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gtjhyfrfga.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gthyxclnwi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtensqohzd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfpzymrq.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthujrzwkk.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gttnmmzlzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtvicplomi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtpaldyiyo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtogpxlmzc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgdlygdp.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtatymnubq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtmozwcgpk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtcjlvjexn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtpywmegog.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtwyoxiokw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtpylhgzqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtwqhayftk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtjeasjipd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtenokipyc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtbylirlbt.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtxpgzcyvw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtlzcozcbg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtgnwknxza.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbmwioqq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetboahgh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtpzqpdgzp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtpjtgsyyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gttzzpyrlf.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtdubsonon.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtptblaqna.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gtfxltyplf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtkzqowevi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtaycdznik.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gthetstvym.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtosfzmqmu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtkjkpsaov.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvgmccdp.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtpbxsmptr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtfhenmany.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtzamdhctb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtwkeitjlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtaermgiui.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuskyzsf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtkmpailoy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtmnteeybs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtvtnxwkhx.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbkxprew.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtioqoyorc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtvimqwcjl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtexpruyfv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gthsjbfxwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtgahjmtkc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtdlhqprbt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gthqxmspao.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtlgubafxk.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtcciuedyg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtssxprptm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtycofhbfq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtmgerdjca.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtgywclamb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdzwpcvy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gttokukvmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtgfqnfyjr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmjugyfq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtbrfnywko.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gteabiqsyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtrsbjezom.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtuwhvmtzs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtctogdxad.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gttvlokacz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtkhnxnnmy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtagaliuct.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtuuztmehl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthtufgksl.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtxrfgqfor.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfeckfeqv.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtngawcvgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtepinvltv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtxezzyrnq.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtmwufqqoy.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqwiwifal.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtwhztdwxf.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpnexwykr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtortpmzkj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtumydurgc.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gthaaorqbx.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtiiegwluz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtpxjprnew.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtqshszzkj.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyukemcjo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtlpefwzef.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtbeqcnyal.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gthettttyi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyookiuc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtwmrpowck.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtrkvsnkhg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtyxtfqooi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtyqkelgog.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtgmkjimtp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gthxrabpvl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtfrufznpt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtrdsrsqhp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtleipcmja.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtsqdqepvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtazwnuxul.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtbbnrsoyn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjwcbxlv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtoxbudcmr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtamuccbtl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtyolgpnlj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtekqihofg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtebtytjjn.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtqnjpbqyl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtldpvgdrx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtofgmtcej.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtoexetxjs.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtzxnpwjxf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqidpaxa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtjcaosegm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtzpehwure.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtdyoairhu.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtogzcvqbo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbtyrxmo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtuigqewlo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtadvhzpea.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtvyvzylyu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtxeodfmzh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtekpvwdjb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtrxqczdvh.html


<!-- 参考信息 -->