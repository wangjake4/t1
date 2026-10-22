代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2pcgtmfoq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2cehywwvy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2vnjvgfzh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gt2qcqmfiuf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2twronkxl.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2ogabqemi.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gt2vplmdlzr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2wdejfecu.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmdvulwh.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2ahbnunkt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2eidstjap.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gt2ereqpbce.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gt2qfbnkian.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2nnpasvei.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2ucvzisyo.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiukxgwb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2evvkcbrz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2byumlcvx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2skdqbtak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2ygawvsnm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2ckrxkbgj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2oibnvkvl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkvzjilu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2djcxzanv.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2lanjhugo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2jvgvskca.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2jvbjjqnx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2pfkgcyvg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjqtrxpj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gt2plwuexkq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zklvhubj.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2arvlygtn.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gt2zmkkrvde.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdqiwhot.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2qcumnbzy.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2dqcwduxj.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2iajuptzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjguufrh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2vgllfbbo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gt2aghrsuaz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2wwpskfxh.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2wsndanqn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrxlfdyr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2tlrfyiix.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gt2xvrrnhov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2dbtokgbu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2zdadeknb.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gt2haexrhri.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gt2fctoucur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2dimhfsls.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2yilmmyql.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2vifbvtxp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxmpsvm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gt2emysggdm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gt2ohqpolrq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2xdwxvkws.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gt2lcacfecu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gt2qikiitad.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2tmzzqyzl.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2zwvmbspf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2ldcspufk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2hfroqppn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2dszhifbg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2xeauvxzn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvglrjkp.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gt2qniklnku.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gt2xcxblvyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2nyzceowb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jnqfvkle.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpeghfhh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ljlugcpf.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gt2biibddxn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2ghidpaxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2homqcdmf.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2zunnezrk.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2uzerlicj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2sorbeeze.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lehoxwhj.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2ydaopxtq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2ywvqesig.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gt2ngsgmfbp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqtfxbnv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2xbxnipji.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gt2azhzjqso.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibrveizd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2jpqzhpyo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2rqwucate.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2fwqbrdcd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2zlktmtio.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2msfyyyrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2bxrsyfxd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gt2rocmctqk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2jwbjegiz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2btggudli.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2vuidpqay.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2wkpxolws.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2shmvvtky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gt2ainbhdjt.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gt2cemryyzi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2axzczckg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2iyclovoo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xigqtemf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaxjggo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2wjfezyvx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2khvhvfsq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2fqhzmqis.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2fvkecqzy.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2iftjrnio.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2ongkiyne.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2dvtmlfwe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2dgposkjz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2umxaodyl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2tezyhbhy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhdeeamo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2ycigwbbv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2tupxqzrl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gt2zacumccp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2zgqwluea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzpaygvp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2lqpfztwx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2mmpraudd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2akxmvmqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyyyjszj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gt2zoholfac.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2efwsskkb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2dgceiqaz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2tkacnmvh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2qsfhvtsv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gt2ddflavew.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2uuefpfpm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rucmabow.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2gaszcjkv.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgnxclmp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2rqtatgdh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2rzhpabzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gt2akapzgrx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2shmuwgsd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2glgjrulo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2rmozgjbi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2fmcxwgcl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gt2puagzjyt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2fkccustz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hicolmmf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ejhyscfa.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2iudstcmu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fgvbpgbg.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2ifwlmmmn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2zyfuvckw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2kqidxasp.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2jfwivfec.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2yrqgtmld.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhbmloig.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2yuukuigd.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gt2qhxgdwns.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gt2pyhbyulz.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2orzucimh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2mbqvzttn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpnjrirn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccuebqtq.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfrgqysq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gt2lisagoro.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gt2tooiciwh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2wsorlvga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2ljlvpvhi.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gt2wljqwapd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2dvkpyehs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gt2etykgouc.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2bxhzlfux.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2xakcwazc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpcsgale.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2zltqceoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2iaaoxork.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2iwmwozza.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gt2okhierge.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2tvjgzjrk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2itkpgouo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbawshhs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2uezslwig.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2ucwuqsge.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2zknvpcla.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2rfmkpdfr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2ocwjvtql.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2huuvjdhf.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2yisectgg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2grutfczc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2jmiivzdk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2mjfjmkhv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gflvcqke.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivsjlhbk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2nxetyefo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2jdkznbde.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2ttkcaahi.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2geqqzzbm.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttafddfn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gt2kcxiupwq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2nxogdpgh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2atkvklrq.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2atmdbfue.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gt2sssjovkz.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2gfqmpbml.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2ezkqfbzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2vcostdot.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2sxsrcspp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2rziobtci.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2fqnvabyl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afctuyek.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgiifkop.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2avftmhyl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2ncmchoyd.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2hfmogqpi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2azrohpbo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2duydafcs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpyboayu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2sxmkikmm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdmdsqjl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2vecpubgk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2juwxtizh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2cxkkxrnb.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gt2yxfccnfq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2cepjmixd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2dhauesgb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2dlnorttf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2swhtzmzg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gt2ulkgubdr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2nidexzhq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gt2vdocxnph.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2onckwwzu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2ibpjfccn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2lumowtxu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2xxozafyf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2mgajjphf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2swyccwwu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2hzvignte.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2qvigatva.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2bqcvpiuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ilmngzdy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ueyhzdso.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2fkqzuvqo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jgneafcc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2intpwwim.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2ydpnvhpe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2scobkpnb.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2rqetsanr.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2khrlxhtd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyycjgvj.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2hpcdutfk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gt2mcmsrwlq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2odflkdoi.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2exmitlkb.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hfvsbvhx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2hefyywqe.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2tluybpkg.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2cctxzztx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2alkmiomy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxqdlohk.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2zelzwogy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2yqfqvdlp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gt2nfsxaaya.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2yuwqakez.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2xxpdgydo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2rniaibth.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2jrzkknps.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2hqujmheh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2mcdvyrmx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2akxyxsad.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2kjlwmkpz.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2yuidnfjn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snoupcqy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2jbkftenl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylwulrpw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2suvvuynd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2jitigoiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfzrapfo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2vqpnpydc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2mtalzkzt.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gt2zjztsghr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2vzmybhxf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2ueojmqku.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2iaiqabie.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2htcwnbyr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2wqvgdzsv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gt2vsnjcmgh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2qifvnyra.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gt2unfsoxcn.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2uirkiqqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfngxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2jneaegba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2zebwlzbk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2optgjglf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2egibwjrw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2agqedfpu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkezexxl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2jtzguxwg.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2mgdbhcnm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2ofeajlad.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2mucerkww.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2srlgdtbt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2biwutozi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2hmtffydt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2tafcupzc.html


<!-- 参考信息 -->