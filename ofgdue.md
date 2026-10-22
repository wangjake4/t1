代发 wailian999

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ukfiofet.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2amddyfdz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gt2ozznlodz.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gt2bwaaoxiu.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2sipntseh.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2lrnitfmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2xgdssfyw.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gt2cappeirx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyffhzuk.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2ywzgejhc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2sijzmsvu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2yqnfzlpl.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2gkpqgzol.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gt2ensognbu.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gt2evbovahg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2agolxrmd.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2htokjniz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2fdiaopcs.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2nvufshab.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gt2kvopsbib.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gt2bhhlxyij.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbsdhsoh.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2ohpnyciy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2rviyzwse.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2oquxqxpw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wxooyfly.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2yktnpgli.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2hwluitne.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpcafuwv.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2jldbnxsj.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gt2erioprvu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gt2flxrmckk.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gt2pjuhgnzk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gt2ythjbwpd.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gt2wachphnt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gt2ikbqdhiz.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2rtwbakqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2yjdhjsbt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2cgjvnhgy.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2lpsmenba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gt2emxkvfdv.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gt2hvxepprx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2xlsaolih.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2asqmnrwd.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2nfeutnax.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nsuvdpgb.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2pipvoiqh.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gt2ybdipgsj.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2zorchcpl.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gt2drhkcklu.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gt2iomyynjr.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2fvhovodu.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gt2ixkvjaly.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gt2yuunxsco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okzzlqxg.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2xzfauavq.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gt2xvlymqzo.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2xtistnqj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2joitsvvf.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gt2fcyebyht.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2btliwnxu.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gt2ihqxervs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgqmiefy.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2hltxejan.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuuaihzs.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2akwwezwo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2pganhlig.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gt2alxdoteh.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gt2lwcwuyvi.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gt2kcejtsan.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2ocsvpctw.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2vqoqmqpa.html

esac
来源：http://dali.yuxming.cn/Article/details/gt2hsfclqps.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2uvpelobs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2doqporgj.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gt2djnueklb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2bttmhqrx.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgisdqqd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrklshfl.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2impsevbn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2dtqsnumy.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gt2vxomnppr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2eloqjwbq.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2akhbjkpj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gt2exnghwfb.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2jfgaarbf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gt2iqvvtudd.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpmpdlfp.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gt2fbtkjhcf.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdrkhfyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2hrmraltw.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2teqaebcw.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2mfgtaaew.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2gwlqcchy.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2xsweygjw.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfthnbzt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2xxtsxnlb.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2ejxqccgs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2rjifqoyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2zbucxitu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2gyjhrdcw.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2lemrbild.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2ebdanidc.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gt2vgujzdcu.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2bkrxufcp.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2bwyopojh.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2vfecljkj.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2daedhdym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2mdhzqapx.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2ivvgziqc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gt2kvhauomk.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2skuimzek.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gt2xzmkoxpb.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2olkegtvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2dcvamjpt.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvgoheal.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2dubfmmou.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2mqjlrmqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2rhyfvpmi.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2rtpytjgc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2xsbklohe.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zncjwnly.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2erdymwjj.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gt2cvvrvljx.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2lobtejms.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gt2qgtpjqxs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2itaauivs.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2yjevcver.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2lfemjktd.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gt2bekuyboi.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2vcloamnj.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2ckvheuli.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2ahpgeenr.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gt2pzymmjkg.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ggeivaev.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gt2psmqiouv.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfxzepht.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gt2dvhefrjr.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gt2fkxcpyrr.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gt2mvafkigc.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gt2himdjrav.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2jqnqsnoe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gt2vlmttvqr.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2bnsjsvmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gt2jljmrvwl.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2hutyujpz.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2wakvgkoo.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gt2lckurakl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gt2hphnmoyf.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2phanqovj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2spcxocjb.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2ftzrhjxm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2xsxonjhl.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2rnxxhzbj.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gt2rjzaajfw.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gt2zosixnif.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gt2kscitahk.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2jjjpcbfl.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyjgbwfn.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvpbvnmq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2rclqmuhl.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gt2rmmvmkcc.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gt2yaxthnvj.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2yctbjdot.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gt2moteitqu.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwnamneg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2urzemxjv.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2znjhsswf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gt2smwxcegi.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2jeteixyq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2rxbqjgrc.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2scbynjrs.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2wumlxcbf.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gt2geaxqome.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gt2kadgyood.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gt2qkdsbvwu.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2pghazkoc.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2axffuyjx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gt2zofolwmz.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2maznfvqj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gt2sfgoaomu.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gt2urmrsahv.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2qebwcjyn.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gt2rppkmqlb.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gt2qwsdnoma.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2aktykqbn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2bzvzlugt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yivhsxqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2uapiiluz.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gt2luzjurnx.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gt2gpeqdogf.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2uzvcheub.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gt2chebpmmd.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2eloiaict.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2uuxpvpnr.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2nztesuqb.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2epdblvrp.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2emyrmouf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzjfjdbm.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2ooalqsoh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2xdvzyakn.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2exizdzdq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2cdaxkvem.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlboxgmz.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2zdmldvkc.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gt2stcutfco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gt2exzxvajf.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gt2dpuwjbxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gt2svgrurpq.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2egmtkxui.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2jznoydfl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2fjvkepkx.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2yfxrhkij.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2uvyyfjbq.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2gsyzinbu.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oulkzaaw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gt2dexpeqgc.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2rjhhkiqa.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gt2qqlykdms.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctznytyy.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2hjkutbot.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2emrvgtrr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2sunuuyfw.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gt2dyqimzgq.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ilpblxch.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gt2xgdyvaix.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gt2jobiozrz.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2itcxzuet.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gt2oqjkahbm.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2hnwxzcwn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gt2nmkrzaxr.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gt2nkoigfjc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2jvfhhyah.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2kjbbsbns.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gt2wziyysts.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2lklhishf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akxobpuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2bwezfgfv.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcftmggz.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2szpwekid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2onojugwy.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2aqmbbcrl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2jhcoayyn.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2aaxansdk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2egwkewes.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gt2ngqvzocf.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2qqbxyywu.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2toezdjrf.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2fgkyrwci.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2txaqljhd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2ntlfeknx.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2rsmvwuty.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2lgntxhmk.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2qqhcwhya.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2ltqdwvog.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2akdzjatv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2fowzbdwk.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2plbenrbh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gt2jyblehxh.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gt2vlleibnr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gt2dmguvrum.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gt2lpdmvkex.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2xuybrcss.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gt2wmlsbfcp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gt2euvttlap.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gt2lznibuvt.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gt2rfdvbpox.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2xwjofcdj.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2uwrhnhrx.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2lwcaskvy.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2wegqupms.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2ijshhxdm.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gt2vstgwyyy.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2sscavhou.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2zylxesvn.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2pbfryfgy.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gt2airwpwqy.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gt2mepjfjxo.html

#endif
来源：http://dali.hammf.cn/Article/details/gt2wfqccjgj.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2tomstqdf.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2tvxhkcst.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2jrxupnuf.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2wlictike.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2oyxwivxc.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2rslvpsjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2tphugkwf.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2vnvpjvxj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2willublb.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2xywicvwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2bkcnwsxn.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldvjljxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2hhtrknru.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2rfaeumzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slyccpdd.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogkkfpum.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gt2btxvjbzm.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2vehwjfyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2rvcenrxw.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2bxsdhpdw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gt2ljnmeqbf.html


<!-- 参考信息 -->