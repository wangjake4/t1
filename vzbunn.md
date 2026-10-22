代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfswssti.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2npcxdqie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2bkslbozv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gt2tynbjbpv.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gt2zpvmiylt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2bvdydeol.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gt2hvjgxtgp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2vgjsjdlm.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2xozmdjnn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gt2fclbjjaa.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2oeojcboj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gt2kxiknmfv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmwruoi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2jqqsoauu.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2jxxgcvnv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gt2puijhicu.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2pdhpdmgp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2qljhovsm.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2pctzlqbr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2fbxiaimr.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urehctri.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2rlkcmsbt.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2cvuizmhi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2bpnduzmn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2trvicyna.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2zztetjsq.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2vepceglz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2tdjiaatx.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gt2akvkockp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxzbtcx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2kivmsdyb.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2yzbotufh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2wxntskwz.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gt2gvbfppgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gt2exasbltq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2yxxltmvq.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2dyifinic.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2apltdvrh.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2ykdbbkdr.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2spdpwett.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2sfcsnggz.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2bjhtddfc.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2lfggrppd.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gt2ccgiovuu.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2ydugbkyv.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2jwkndowh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gt2kavhiokh.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2xncqhjxk.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keisecpw.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2tyxvsifr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2hhdmyjar.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2deggjzfo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2uaiaepdu.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngdrcavk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2dytlywxv.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2qfpdigie.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlsycuzt.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gt2chshsycd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghoatkpj.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2uhkgqpnh.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrzwykcp.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2onzueooh.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2udjiywni.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2efhkmoun.html

esac
来源：http://dali.shuidangran.top/Article/details/gt2kdtceipr.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvjgcrlf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gt2qivyctbk.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2aplpywxh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2aqpklueu.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2cwccrzgn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2koygwvds.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2uqsempcl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gt2tpssdvtz.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gt2jrhdzgnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2mghftdjx.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gt2ixmswxqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2harfejwh.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gt2qjmjmhzd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwntdotn.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2qocjtvxw.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2ytiyirdu.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gt2lrfogwqb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2gafbsnkp.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2iorrqvuz.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2mftigmvn.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2osggkubl.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gt2brsnbxea.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmtlvmis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2gduklewl.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irqrepby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gt2cbztrxfs.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbvbiuyy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2edtrwyrf.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yennsnfa.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2atawiqht.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2uisdjjxu.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2mherkzki.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gt2kjabfakp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2ypsdpawb.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2jlebtxje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2qcoebpbz.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2qzndjioc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2jwrfyzin.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykwjdoaf.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jbjdtadq.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2kcvtguzu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwwlalre.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gt2lkrwwwkf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2uszipuxf.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2qlqusxje.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2stelpwlj.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2qfiryebr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gt2hgpblxzu.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2tlrjwdyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gt2koakfers.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gt2jixdluan.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2ebwyfkch.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2ykaxwedk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gt2xdxazeqi.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxxepgtg.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2hpfyvigr.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2imypfbko.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gt2tocbawfz.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2euegghmr.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2pnlhcfpg.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2divlbtfr.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gt2jrwuhikw.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gt2lcydmzab.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gt2wbiedlxf.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gt2clxnexqt.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2rfqklgsw.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqxeocad.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gt2nknsmtoh.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gt2nndsfpqr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2cxfxbkbs.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2puclmjkj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2uzcaxgyf.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gt2aenwcpio.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2gfubolgw.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2pbstjddx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2onxfejzg.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aefyocwv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2vhlpcnxl.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gt2rujxjgyh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2vxwamttn.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gt2veghtwzu.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gt2rprqtvub.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2jpcipswj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2otvdusov.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gt2ggjymwui.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gt2swnngesm.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2rakatvui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2ssonymgy.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gt2wqfkacrv.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gt2pxymwibk.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gt2tjqqchsb.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gt2prgxqawm.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2fcmoqulz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2duqvjqqy.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2uenzgwcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2prbwhjay.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2rkknnbbv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gt2ofhyuueh.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyshzqrq.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gt2xuwhshlr.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2xgsjeare.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2dvkghcjo.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxjryobt.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gt2vcyrngcv.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2cnjroomm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2ncphubos.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gt2yaxdtmro.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gt2ympqfwwo.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2afhxdclx.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2oieodfew.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gt2tjzrhnjw.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2wozeeoxb.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2owbzvxca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2qgslkvcc.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2yagtjtcb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gt2rgaetkwu.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2aahmzrlr.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gt2bydgkjqf.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2kvvfpcmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnracbpm.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjchywez.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2kakajkdx.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gt2jsgclxte.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2avcfpxzl.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2liqipuiz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gt2mdxdozwe.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2esdxvzco.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gt2fesvdxfh.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gt2kdwakuma.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2mckkucmi.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gt2uvcbkuox.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gt2dsbystfd.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqigzowt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2cfmfwcpq.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gt2faiibnec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gt2fzodjyxi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2gekrozdk.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrqkwkyb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jmqtscck.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gt2ruawyvvp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2brkqgtpl.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2yosxvaga.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gt2rjkbebkb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gt2xvdbywny.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eebnfney.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gt2ppsuquhr.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gt2hvjfciuc.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2vjmbnirb.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2iszrinvs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvlhwask.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2erpybqsc.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2pbwomjfz.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2sheoutku.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2iatgevju.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2qchrlrym.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gt2meokuedz.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gt2vwktgxct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2hzpxrkzh.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zznqzdag.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2dpxosbml.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqphhnqj.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gt2itefnprh.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqkluflv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2aefxfayk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2wgieanbg.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2jxixdwme.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2kliaqdah.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2nlnedfmn.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gt2ygrrhwkb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2mqwopqzn.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2urwutbfm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2ojqlqyfo.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2oavdsqbj.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2oijmltvl.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gt2xeclsofl.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gt2xgyjgssw.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2kaqynfgr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2agxdzymy.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2jftfpmvx.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2amczehlh.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbshrpgh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2ontzrpin.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2pirsgdnl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2fawtjzpl.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2skduhmfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gt2bwwuateb.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mivyrlvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2ggmvjmqc.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjgybchb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2rjyhtudz.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2pferitvk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2rnswbqir.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2zamwxztf.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gt2slatgeln.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2qfzivztp.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2yalzycvd.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2xhgrrrvx.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2plvchtjx.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2dcsrfifn.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gt2qivrasey.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2mxjpyvic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2bklkmvzu.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmywwvzk.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2welguuia.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2aksuahup.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2djwlurvb.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2cgyyfdfa.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gt2bkonkujl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sdlrhwpz.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gt2fmvhemja.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gt2jclwdjoe.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2vkwwmduu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gt2sewfukin.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gt2seqilzlg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2sfjorrkp.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2arhdfoat.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2lqvzuuyr.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gt2ovgustcx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2wkxbjdmy.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2ckekcgty.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2ukmmxhmv.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2odudjbxk.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2gecptwun.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2ivtcdkmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gt2mocciiqb.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgepvypj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dheltakr.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2hlyrlqrz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2dyaewbmb.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ixazaxdg.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gt2zshgpgtx.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gt2fcofwzla.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hushwald.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2jksbvbbs.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gt2easuzhhi.html


<!-- 参考信息 -->