代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2yjhduxao.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2pinnoptc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2leoznqck.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gt2oupquhgc.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gt2achjqmzl.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxdnwmfo.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2qpbfyzee.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2hkcyyegt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2ftvqjhme.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnblwbig.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2hktwdhci.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxoedfsb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gt2ieuzslsu.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gt2nfkyjlmo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gt2qdezlodk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2sikytvqs.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtciuiyx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2rlijzexh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2xtptvbow.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2wihadoel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2emnnuqpr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2vdqkrhwz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2sfvtydbg.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2gkiepkgi.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gt2gvwxmtud.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gt2bktywwvt.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbgcncsg.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiysyqxk.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlujnoav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2tglhfyju.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2taqzntrg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gt2vbmufgwc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2xwtfazjx.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2qojgjifa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2igyvduuu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2zkshnrvz.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2bvqplozx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gt2bjitnlet.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2youumosx.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gt2jijtlvbe.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2eqligipq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2rwrqbftp.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2otptydcz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2xcjlqqzv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2qnjzuqiv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2rouvnhhg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2phmawoec.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2edkhamty.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2afhuappv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gt2xjhmqlip.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2gxjzodgj.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2vbmixbhg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2jgrzwusa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2vokayffx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2pnuijtwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2mhctekav.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2gxdtbbtm.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2irdwixpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gt2cwzggknh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2bjilclof.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nxodzdbn.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2pljqljey.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2biishpfc.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2ritumwwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2albjykwx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2sckhwtod.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2eccjwjhh.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2kkjofuza.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2esvyztfn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2pzdmhaqe.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2yvubtltj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2oyqymrij.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egiftnck.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btrulbuv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gt2cwaquxor.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afprzuhp.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2djpzgfyx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gt2qlhpkocm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2jjdgocjs.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2gracjcij.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnqwnsof.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2sciyknvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggocvthq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2wdkgmgwd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gt2xqqkaheg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2hibjsfgj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2iomxplwy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksnjlqcq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2sbfbjgtv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2fjusgksg.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gt2zvwgtayl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vwerqonz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ldwepfrr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2arhpdhmd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2vwswuyee.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2rofxyyyf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2wbrrtkwm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gt2lxexgnzr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2mnozbwam.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2zsuprrvh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2sutpbynw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2cmwjwuty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2xybwxdzn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2tvveziwn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2wpjvqnbj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2arihjwrr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjcaionk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2iiynybgs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2znucwfwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2juknpxmu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2xjgezfxi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2laehpemv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2nlvpyhdi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2ugefagqn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2fmyirmcb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2rveacrvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sngwujsp.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2gsjxzwvi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2jxvdwiah.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2jbqamvau.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gt2qvohsszq.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gt2kzqvloqa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2ljmgmqey.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gt2wpopjmhz.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gt2jmdqjgbs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2qafeaiqo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2nymuukcf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtnhomde.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2fuhiewmk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2cwgltkqj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pexmugpv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2lqarsmqf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2oyacyfcy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2vuappepv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2xptraqie.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bajwjurg.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2geberhfz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dxqcgwlb.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2yfsfcqqr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2zwgrozqs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2kljvimhr.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2jtegktbd.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2rwwmqpva.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ueamaucu.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2gvnbrizz.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2spkkkvoc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gt2fpjtrrwy.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcgnzoxg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2qykbjjip.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2pzmoaqal.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gt2mtwmskmj.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubjkrnpc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2nvcckhsa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gt2ygtlyhpr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2vyvusmmd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gt2eflsfmqy.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qryuuisv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2tpqpcuhx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2ofycgbqu.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2ipildoxc.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsocslif.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2vykcuxaq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2kfjxyyeu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2vyqsiiaq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gt2mshfspmu.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gt2pflwjpar.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ihwtrpev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2ddyuhzze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2vfvfrfxy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2laepyngr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2nzgmyraq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2qadcaybi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2npobwgsj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knqygwyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2crulrhfj.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gt2haqrngqh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2ahboywgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2qecuaijn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2zpiyrhbj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2beoxinyw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2ehpjnysh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gt2avirxsss.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yniiuxii.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gt2ptonbzxw.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2ezllwacz.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2ubtitxtc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gt2vjdwlkah.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2ebsmjwnt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2fjelqvav.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjjjerdf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gt2lylquasz.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2isyahqno.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2dkyqumto.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2clnhedvb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2daslwwme.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2rgfxmyjl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2gghorblc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2utwasnlj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtheuwsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2jiakhheo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2lsypwvqg.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2vxhzdulv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdcadoye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2sfktkpaf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2wxswsxzl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cotztgip.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsfbsikd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gt2vnqkvoqf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2gbzarrep.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2ubhprotx.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2otykplpx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdacofyx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2cgwzhkxy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2anzutplu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2uzhzobpn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gt2afglrsio.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2dsofialn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gt2ogudoaas.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2hqkrsici.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gt2gdraezxd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2zpkplibz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2cebcbiwu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2vslikoms.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2qhkgpszh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gt2uaehnetl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2onuuldgu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2toumgnjc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2pptrnuiu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2voaicmfo.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2hliusfcy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ftizysql.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2nserorff.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqjjucbq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2zayldose.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2lqqzmoib.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ipjhqntl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gt2hampwogv.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2niaujitt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2ssgvczpi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2nuweupvw.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2cebviyzx.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2tbosuaey.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2dyazsgbq.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hsqpsuvn.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ludfojtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2hkdnhivf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2fayjylqj.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2pgsfklwg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2supxyotd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2fwixiuui.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2uximxozn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2urwzxuwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xjqlrvqh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2yuautvhl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajismuad.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gt2lcpxtxsf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkqjvbji.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gt2rhhgobac.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2bbzgbwgh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2fpfrnpcw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2vusonzit.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2lctrvpwb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2xtammxgd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2mkslaadr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mupvtefq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2yiguoioz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2xkyucndw.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjigctfk.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2xcndlhyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2lrxscemi.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2coxvxhop.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2quiffxvm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2jabgvpjc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2jrqdosep.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oewqinww.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gt2bfcqhoee.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2iyardpao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfvsaiqz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2isgqswps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2hilfagih.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2qndmvtdw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2rnofsarj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2dbouhamo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndlunaoz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2ihlaztxk.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2wnfjffub.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2uztscwno.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2dmfvrjar.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2nkypxidc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2dbiiqtby.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2htxnekfz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2itcdpsen.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2nheqeoet.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2rnasvrbm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2qmwbypck.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2eletivvh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2jloyqxod.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2idaxpdxa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2fuzkgscd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2mphkywpz.html


<!-- 参考信息 -->