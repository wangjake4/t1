代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2femniqvx.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2jpkovfta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2dncxvong.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2vbplctsm.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2bounfrul.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gt2ywgnchqq.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gt2gaitiish.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2gvsgfasy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2ffjkfxko.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2epgluvka.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2zvotfaws.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkkjcsso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2segxvjrn.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2fmdrtyui.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2smmrjgiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlzkgmej.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2avgbefah.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqrvqwit.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2mubcipid.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2pyrtykmh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2wupzrmoi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2aqrmmdjq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aizfeats.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yerikjdg.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2hhrzzgrf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2ligfunrp.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2vxsqlfrl.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2zsahekun.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2rckfxpcp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gt2icmpobyg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2uryxvcih.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gt2glwdnjig.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqqvgddy.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2sdmjanpf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2gvjsylte.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2xlvesqel.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2tqxhmmyz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2sxhznudd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gt2fuoomayk.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2khjnmvaa.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2nohynhvu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2gmofhgfb.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2kgdmuaiw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2bjhnzcij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2yrwtpdgm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2rqnbevsj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gt2wahqonht.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2bksisjnv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2tigeldxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2yytdnsjy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxwxuhp.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2ycfhxbrl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfypficd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2yzsikgom.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2xarttfui.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2dgkqsawf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2sureydyl.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2naqlknod.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gt2crqdposi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gt2ikjgxtht.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2sfphsqla.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2pdqzoccj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2joaexfvi.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gt2vhtmbujs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2xadkrzsu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2ojfemrck.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2djvnhxxa.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ymuqhvxw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2eelupyyk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2drxwxglu.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2thtaaaum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnkkflwz.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbfxgqmz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moavjvhq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2syieqglw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2klyydxsa.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2mwdfyoab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2ddszeaap.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2hjmdxuds.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muwelmmh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2mixrkzna.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2naqntqos.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2marpqdvw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgsgvczl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2svjetscp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2phryvxrw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpzvwgda.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meaogmak.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2qqpbmokz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jztegeyk.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2vwxsuyqn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2dajkedaa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2pktgckpt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbeoajjl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2zbbbnami.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2hijckimw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2ansatmsl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gt2rzkvyunv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2rphppehn.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2nabrduwt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2zshlkrek.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ferwecws.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enjuvjsp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2bmrqnpjr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2sgbmxtfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2sbgzvbbp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2ooyppvhn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2cjzbswqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2acqdvxdl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2cgrlpifj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2mlgefneo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2dojfxeft.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2ytnzfzzf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2yvmeyogl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2lyewriit.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2thyntgvr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2gudddxwz.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2jygbzazs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gt2qzuljyac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2spuhbogv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gt2bsxfslas.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2zfmhwdyq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2orgdalpq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2pryxbcqr.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2pravfcei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2eruquxwh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2wbkrluok.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2wzbsmrva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2jbwxkufa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oousaruy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2oeljdnrl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2fopeccjs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2jhrtogth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meysxbjf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2lbumiyaa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2icgdszkg.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2pzqmjrme.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2pxojldnr.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2tjxfvnhq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gt2zlijutic.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqkabtkp.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2irbahmad.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2kkqtkqxm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gt2jcpsnymb.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2uthuutka.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gt2dneigdnk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2ullmpjqf.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2avinckty.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2uceigmey.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2hvzksfut.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2xcaguoey.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwjyyees.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2gheaaayw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvkaepuo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2pbmswhmg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2yhqsggmb.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2wymwtzru.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2waakzswh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2olkizslg.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2jwabrcag.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2vspxwgus.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ircarmqf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2qsduheof.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2chemtglv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2iglfvtpu.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2jnycvwum.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2nnnvdlwq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2ydflfvvv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2emutphom.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2sxktdund.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2qcfpvooi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2pferrpzh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2rupjthkg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2pejgztxf.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2azdskput.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gamdqijx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gt2pdnmmscb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2bjcqljfg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2xmnufccr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2xwkmlpup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2dxmuonms.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2enykqkbe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2jobzdgxx.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2gbmjrpja.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iklservc.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2xxigagyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2gytsjflx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2oncgivzf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2drrfuisy.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oijiqunp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2fovcodzc.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2qtmzrnnn.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2vfvhffos.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2hrgyqpqs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2azwkqrnz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2hauqqzgh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2kcynnhyy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2agmrckfl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gt2pvdfnsmr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2wmfagbjs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2vwoiytod.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2fzkoafsq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2nxsfeglc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2macjelye.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkprhtqo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gt2qgflfymx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2bozafpuq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2hgmvokgm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gt2jvevhfxt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2sygizdiq.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2hixoovfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2hxgayfec.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2fdqqraef.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2qkjwgkqd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2sqeahrux.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gt2kbqducoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2jthysfmc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2oqxnrxqa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppanmncx.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2cdbkyrgx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgfqhxok.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2crexzgtq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2yolcbvqd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2bvkoujdz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rqhufowf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2bebtgfer.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gt2iiucbukr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2udlcbcnp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rusqbxgs.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2ntqdoifs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnyfsjrg.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqrptexh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2tgklklwd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2phvgptvq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2mnrqhtam.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rfhmbwje.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2husdqjhv.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2nwnrmuwq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2lygfckgi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fpuohpfu.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gt2swzjvlby.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2buqpogoz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzeswkhi.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ksaojfxx.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wfgjmask.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2imewbtct.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2jditvwrh.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2kuotlzhm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2fbeydxtw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2niyvdqtk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2tvfkpoak.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhemdabu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2dmpuapmz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2jbrpchdd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gt2hsglecfx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gt2oppumfkf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2jdmugyut.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gt2fwxqxctd.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2niexiyoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2wjkdhejq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfyayufz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2wkjtlzkr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2fizwqqcb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2mjbfrvnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2ubwpgpov.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnxwswjy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2ebqwzsqe.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2rvgreugg.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2rhgkuxys.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2wvwotfrw.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2czjovxbr.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ikijewcg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2emsroahv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2onfvdpvb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2hmryrikk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2nflishhp.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2oxjteqhv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2dxinxoqx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gt2flznkhlt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2zdmxpxmv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2nbylhriq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2vlwcqvqh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2eivvxlep.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2zyspcopz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ghpqimbc.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olwhsqoq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnfaenkf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gt2rtjeezbc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2eekhzcjy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2muwxayck.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2ykrdoxtx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gt2eqwkseqq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nurncpmh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2zxfteqeb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2lqrztygn.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bsqsrhal.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnbumynl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2rwidfvec.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2txilzqbm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2nopulkhx.html


<!-- 参考信息 -->