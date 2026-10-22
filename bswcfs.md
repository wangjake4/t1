代发 wailian999

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gt2pzdqogtp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2pywdnpmi.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2prsjbfip.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqgpijpe.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gt2khxiwiis.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2ymiaotzo.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2zoudqsgz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2zswzfcxp.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gt2ehqehslk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2kvtzyigv.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2lkhwusps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2lgtsypds.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gt2weqxgdgp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2ejijvspq.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2yuhxhill.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2xpfyjdxp.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2grhqsfvj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2ypfscawq.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gt2yfmphslr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtejwfom.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gt2tciwzfyb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2oyiazpjx.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvarpikc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gt2bxagujtc.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2xyxrsyrq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gt2wditsrzf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2qxcbvmfl.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2bdxoogxv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2zkxxupos.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2bpijjxhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggsvzrtr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ndjzovbk.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2trpmsvve.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bkdyflrj.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gt2wkzurmgk.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2sjauifpe.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gt2pwfwwryh.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gt2oxlmocpv.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gt2nkylstyx.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jywdcmne.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2ovgbjiya.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaaqoyzm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gt2dvdsjuvg.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2uckzwkfj.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2lnternyj.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2sjxancrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2bnymqjoq.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gt2uttuxdkx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2oexqqvsp.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gt2iuftodlh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2ldssfbpo.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2tklcgsxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevqsfl.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2nuorccie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2hrdiqapi.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2auimlcxh.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjpjatib.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2aibmsyct.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2rwtvdvnx.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2wopddomu.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2qwankumf.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2eihljheu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2dwbhsywa.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gt2gkjtcack.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2ejgllegz.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2eblayghr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2btwmeqyz.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2axbsajfe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2nxslckei.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gt2xxtbkoyr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2jwntqpei.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoufacsz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2nhzjbkig.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kewynvav.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubflmoki.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2qqfxirun.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eedcyhma.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gt2zntpgtct.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2bpsmfjby.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2tylcbigp.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2vyiqfxjo.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2cgmmkdet.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2tleaphwu.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2whvxmixn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gt2zlxewnvr.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2ixltckox.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2iuptqhoo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eorxglps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gt2dhxjzvog.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gt2umrmnvre.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2suaqvima.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2pbqxcxtc.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2ajvyufew.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gt2valbzkfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gt2zgyvxtyw.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2miqgltej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gt2yepoqgiq.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gt2vsssvnyy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gt2jkrzvytj.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2peifmlyb.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2xkzohzsh.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2ritflpvd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2spifvlls.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbekhvur.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2xtlofusd.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gt2mjitwado.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2ruigfict.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2eurskyoi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2dieblkgt.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2vxijijdy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gt2xkthofzg.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gt2idrntsev.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2vakjdgei.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2xsmkffke.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2jaolcjfw.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gt2hrecbfok.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2qqdrydmq.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2zjbiuwps.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2vmxuxiqg.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gt2yuhgeliu.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2syonbymi.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2wnwigmjx.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhbtrbci.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdwrtpdr.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gt2nekqniua.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whkidknz.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2flbeqqed.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clnprhtw.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gt2hjeuvvlp.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2ncgfjqcj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gt2yxgkfflg.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2yllrfzfn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2mvkponiw.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2cumbndxk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2kjklnzxd.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gt2dxnkdwoj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2nvztarnk.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2alyeimrh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2gshrvlwp.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2kfjzzcjt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoczsclk.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gt2cxufqdut.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2iacnrlsy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gt2oweebohi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gt2xrcwaicj.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gt2wdpryscb.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2nywabcrv.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gt2ncwhmvnj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2hgntpntu.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2cserlnso.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2csjogtbp.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gt2igmcdgta.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2ezokpjuj.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2cytgrtov.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2vqmnjtma.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2fxghdwiz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gt2hmchjrjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2cvkhoxyf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gt2uolpnxqy.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2wfkvfwce.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2uofzwyau.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2kcrlhdny.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2kawuajjq.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2psvmjsid.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2lxmivktg.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2gkesugmz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2boluczqe.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gt2buukmhug.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2guppqjgg.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikfdamyh.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2tggyfprq.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2fzuzwulo.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2irdwcoxk.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2tpxhkghx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2bcfghucj.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2fzgruwbg.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gt2fhjnbnop.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2bnnqyvkl.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2bazqdnnx.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2jkbyrmxo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gt2ihbfpgwc.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gt2eeiuqeri.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2xynsgmze.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gt2sxswyrso.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gt2pxniwudj.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gt2cfuqlwlu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2farshvbn.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2yqbopdpi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibnvmvrv.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gt2eejjzjcb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2kopeclnr.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2gcwyiwbe.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gt2mqimcndx.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2ktckimtd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2uudcljix.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gt2afhhmavf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gt2fpttnaqv.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2mxrwcbvb.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2ajgyrdjk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2oitgedtd.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2svcyevkt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2oculvbsm.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2vjerddtp.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gt2iwolqtsj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrxeytow.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2xcsyjeyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gt2mndbsubj.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2oexkfjiy.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2wajcdkvd.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gt2rkmzgbgd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ainliwbr.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2duhkifec.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpcchody.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2xdcuevdm.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjnpaujo.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2rngliupc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2dxzgaydc.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gt2zoreevqc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gt2ndbvpiok.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gt2rxblgexg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2alowlhti.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zndrmajc.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2eqpwwmrj.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xihiuoft.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpsilcm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2vxssqwbk.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2lcbfcqoq.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gt2xmskcxiv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2npewnont.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2rilcdhos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gt2sxhgdxux.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gt2xxyhojqu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gt2mwmdxiry.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gt2uuxczlac.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2rimosyev.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2bjtzdmcf.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2vflzjaws.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2lvgtfsci.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2gyneesch.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2llisqkae.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2eonssser.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2cjswhmrf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2wcpmhdgz.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2kvbbrpua.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2lesfvewv.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2gqcyglzp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gt2drlywjkf.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gt2zuastwcr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2dwqjnmvw.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aejlehdg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2gzzvpvhr.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gt2njazziss.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gt2doihcytk.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2tepteklp.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2wvozyerv.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2khopsaxj.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2ychbnkgv.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2qpuawpsk.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2ebyqigkm.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gt2bzfahoko.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2actrhlwc.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2wofagyjs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2tgnphahn.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2benjbxhn.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gt2gagfaafr.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2icwvhvmw.html

#endif
来源：http://dali.zycfv.cn/Article/details/gt2kjvcfkcm.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2gsqqhojl.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjyqlxzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gt2skhtzijm.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2xwsnofmz.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2tewqpqhj.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2lcjkzomv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2frlgtwri.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gt2ygrupyur.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2hpgzqezg.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2diiogdhj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2renlutuv.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tymofizy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2guoztfpu.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gt2zeyyacbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2qhkfmlse.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfhcorhg.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2rvgdukwa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoxhikx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2pwiszudw.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gt2ynxynffc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2aysxuyqd.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2isldgodd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2chtkkwus.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2vacclwhw.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2jvdntflg.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gt2udhhmckk.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2pnepuuko.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgncplon.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gt2rtuqgdez.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2rqrovlar.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2upcdnfyq.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnvxxkqi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gt2ezxfmwzk.html


<!-- 参考信息 -->