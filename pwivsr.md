代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2krwblzzo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2wcvifykw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gt2mkjqmfpq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ykaxgfse.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2lwhwymyd.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2hfuotkca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2faoergyt.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2kgahuzfe.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2uuxpynkq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2pauroqtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2xnyfpwei.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vctlzdsz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2xgntqpah.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gt2yglzvsbh.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2xndqrjdg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeeqawn.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obasqfda.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dkrdzvhh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2ewaavioc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gt2wtmimwjo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2oluehtaf.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2myozjlyg.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2ojpingvv.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2gvhfpupu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2waaqfyeo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2apozdcji.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2kdjkkjvs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gt2uecetnia.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2jbmczdrv.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljrdcqby.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dawziwgz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2vgafylcd.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2xsayxqed.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2tvnljzft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofdgwdgm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2qbsrfiug.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2kgkiwgxg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2flnijxim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gt2ujymkudd.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2urfnennu.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gt2eodcvziq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gt2dgmxgzrb.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2vhcgbtcv.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2pjapjjzo.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2fnckffuw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2ecxmeeez.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2iwbgtnca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2pggirpen.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2qyrfwauv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gt2xudlqgzl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2opqccret.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2lthocxrm.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2oyndtmqq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygrtvomi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2mlrqasod.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2zgcvdqba.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2wqnowetw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gt2nlfgesia.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gt2izsyrzgw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2qbldyxgd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2chmfxixt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2yteqntrb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2yuukszfi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2qdtgskbh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2nkijnymi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2adsyzcjb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2qksvtihu.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gt2demsczze.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2asgjsyie.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2nrbnjocr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2fdylacwh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2cdpdvgxm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2fukhsmty.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gt2jubcufib.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gt2holpkfpk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2krreaqja.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rcvwdrjj.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gt2xwsuaajv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lwukpjuw.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcxcdqqy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2uudmjkdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2tlqdddld.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2uvlrtyie.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2givfttwj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gt2zyyidaas.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2uevonpmt.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2ktjbpfye.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2plzvqyfs.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2faimhomf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2bthbkoil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2assafslj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2cethdxgw.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2jgjmkmwi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2ykitlvye.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2ybubczfg.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsegsmsm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2qhbqiese.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxnlljqr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2vfmlkuew.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gt2vzmscjio.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2whplrwwp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gt2rudyxmhh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2xlmkyjgp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2aemvposw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2ymedmmny.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2nphffimp.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gt2gncayedz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gt2sgdsrnar.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2hjklxlzw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2qywkmhsf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2rtnrdwwh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndezziti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2judmhpvk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2jmbrzggh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2lahmblez.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2viwmbtlf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjouqvin.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2tmtatzoh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2tcvkibgj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2bitlyawj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2hcyioead.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2wbbvrboa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsblyphy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2whucxbrx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2oavcqgey.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2buqdynxu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2zdxkkium.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2fqfrones.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2npqyncxa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2lqcocbob.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gt2vimbfyym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2bscvfzct.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2xpazqhij.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2bjdravwz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2yonirxqb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2mdvoernt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2lnbncgmr.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2xqvcaxdw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gt2gsexrwrz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gt2wfvpkdyn.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2txfqswaf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2laitzkoi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2aysnitsx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2zevzzime.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2ybgcjczp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuhvfykv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2flzbtrbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2rcpwdyng.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opwblqcm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2drsxayvv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2noxmoxho.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2itdzfhtl.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2dxrdziwv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2scgskrzf.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2irvuzult.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2epysbvpz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2igeankxs.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2lpwpsulj.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2cqezokhb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyacnryo.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2csyjotgw.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2ynhgjwps.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2qqdnrwte.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2bbbtagum.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyhguauy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gt2ppifzrnm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2cmjcmeyl.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ixyhcufs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnwwnezf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2fedikhfp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2xgijscsp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gt2arkgeuqs.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2lxnkyseq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gt2vmbgqlqz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gt2fxivjasj.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2unezvinh.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2osatuocg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2yjgprxwt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2dpqcxoow.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2hgmiflgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2qwpatjhf.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2axhodbmp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2fvgnobnf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2tbjuewrd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2ghdgfdzj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gt2kefqgnid.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2tuwozgyh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcgjqqle.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2oudpuxmd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gt2qttesmti.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2bmrpdqio.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2odkamuiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2walxppep.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2ispknxum.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2cvvwetnj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2hhoaozjo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2rhtdmied.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2prdqgqwc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zodvetud.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2skywvrqi.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2cycsttvr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2jvexaueb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2buvdcfss.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2mffuhabi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2ooeajaym.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gt2rjaugyvf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gt2omezdhtn.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2ztqdezbw.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2ftclohwy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjihrgwx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2vramkgyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2zdadnpgu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2blcqogxd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2rgddsues.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcowizmt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrlydhxs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2avieubit.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gt2xzqgzfpm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajjofstw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2btpujnod.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gt2xlbkiqrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzfpptbt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2huplqntv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gt2npmeiuxm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2bzxijprs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2sefvnjdm.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2cacchzof.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2xifeebvq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2rxtnqsdb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2oszeanwr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2vmgdtsdf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2lzdgkciy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqxukwct.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2yiutjhrn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gt2iwbgfkaf.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2wytnvovj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gt2vcsuuovl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gt2sjoaypdt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2xrgbczpz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2voehsudi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rnvbdmpe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2tvkngtdt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gt2rksmidkm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxonpxzf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xzvgvzfx.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2tjdmmaon.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zodfjggp.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gt2raafabtp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2effrnkea.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2ucvogfhw.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2aiueixfy.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2gdcsshmi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2ykdhulmy.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2skejdyei.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2khievnic.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2dfzmzpxx.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2hdrdskpz.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gvefatcr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2opnvondc.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgloymcb.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupcidmg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2kuxacrms.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oleswnim.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2ilwhtkeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2lpqguxzv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gt2nnfuwbfr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2lvvgmati.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2eyyseobq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2joflswrm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2xweqxysq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkfxjuus.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2zrftpwwn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2zbqqrxlf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2oaxifiai.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjmiyliy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2vilsghqm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gt2owdkknjr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2hycgdklg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2anofepob.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2szmhkmsk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmmwmivf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2nbrvjerc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2gruqkyfy.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gt2flmetgqa.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2fvtfomyg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2soveowiv.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2oquiharx.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2hwkusqwq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2fltscvap.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2gdrofxky.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2ucrmtkwe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gt2cczfzmny.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2jtoieghw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2wjhgaejy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2ityxmumh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2yalzikbf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2xipsucim.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2anntxida.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2cbqrcriz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2lbwtytyu.html


<!-- 参考信息 -->