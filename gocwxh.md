代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtkludkyuq.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtrkcxgjax.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtbwxokumr.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtrxoapzgp.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtwrxfgubp.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnafcuoh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtbjlxxnjp.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtpazesjqw.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtwpoxqlzi.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtpslyaake.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtaficribn.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gturggzipb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgylyiqa.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gttuyqeopt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gthwopcyii.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtwjibgtle.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtycmxyaio.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtrsrlvkwz.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgcsheze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtzwysxetp.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gthglqhugo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxyjjoqy.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtmgovfarh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtqsowedui.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gttbwzdvot.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtdtcbiirw.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtatyhyoku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtsktjgcgu.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gthlkajiqx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtqxgmdbsa.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtrnuplpga.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtfxhuxivm.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtiotfwost.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttghteflz.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrubtjrf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtqpldoawz.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtefgenkuy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtcpeehxzt.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtqffjtijy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtcpgkwpsv.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtmofvhzax.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyxbzoba.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzgutojpb.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtzhbjbtmn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtvlkvkzxb.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtrvfrwimf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtwejxfnzj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnokxizxj.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtxhpdmtxc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpylxirhr.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gttdxumyiy.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtetrgqvhx.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtcmmdqybn.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtzeolzhyy.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtotszwziy.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gthzgolktq.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtvalgnsfi.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtyhkqttlp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtpoeejosi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtxqglzsxl.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtlensudnp.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtwumophcr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtrtdinopt.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtlwsqyfsa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtvjqpvghq.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtmlzfpwmw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtdwhupkbi.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtqylscipx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gteagbqpjm.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtsdmdkekw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtvjazxptv.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtuaqlmmak.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtyqnxlqdo.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtrknowpzc.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtugksshaq.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtkmfzffmb.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtfxcevthe.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtvdjybpkq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtxrcutsko.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtiqpudvtw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gteuisaxrs.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtpqvsgnwr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtxdgvbida.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gteipundia.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtqudugder.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtskhthsvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gthcbqeuxn.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtjscgoipt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gtwsdkidqx.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtcpxujced.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtekmezpri.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtdhudfxyc.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtcvdwrsmt.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtwyuctpze.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtziswvtxw.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtglhrfbqb.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtnlxsdhnw.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtflodptyu.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtopspyecp.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtrmyioomg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtselgpeuh.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gthfwnpwyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtssgplrhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtxqpfbucz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtsskzxvql.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtptsgrgif.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtqfokiisi.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gtfjqxywzd.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtpduxtvqb.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtpllsbrza.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtflofhpix.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtolnfonoi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwtdycjht.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtgqlueosy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxikxhwv.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtptoocpvq.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjgmbiats.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtepbezyww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtnncdetha.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtfwoogslp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtolqiycdr.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtlbxwoexz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gttwkvhorg.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjsfjaxl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtgwgjjecx.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtqkvhjseq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gtvgzktmrn.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtcwrezdvr.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtlncnoohu.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gteprwdrai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gttbqlurnk.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtozxculyp.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtmcmcuirv.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtilcphzqs.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gticxglnmx.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtccldlzaz.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtlvilfkkh.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtpfxpcjzv.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhvhbedg.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyxkubcxv.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtzhbarnvw.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtcudvzazi.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtccmsgxat.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtnhjcjpvk.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtxolltcim.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtdluyvhcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtcypzmrxq.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtqytrhymb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtigzkywoa.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtomrtrqhx.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtyllcxfoj.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtdalyokxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtwsnccchc.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtdhqqywkx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gthblqpddl.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtfuqceuom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtfiashddx.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtypvgrxzq.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtipveqy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtmghylijz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtxkxnfihc.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gttmxjcdpl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtpmizbzcg.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtcyjdcheo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtdpfmpraq.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtslwbzfny.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtjdexxawu.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtjonyyblj.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsbwalup.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtatxvqjwi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtlextuoja.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtvvndvrtm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtcxyunafo.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtdpgwidyh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtiwrvlkfr.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtjpjpratm.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtlgoqeqli.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtucrvksbq.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtywnrxawh.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtphghcpjr.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtmjkumddb.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugevscwx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtgkunxlvh.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gttdgicjit.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtwhiyhspw.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtxlbdafuy.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtceupdbce.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtmxrwqqvm.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtnpkgpnpn.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtygmzloed.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtxmfszvvq.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtdblrvftw.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtxwqlmvwu.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtldjvnkbb.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtuxgsucyq.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtkkneveki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtxsjbzlih.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsnpsjsr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtylskopii.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtqompsdoo.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtahkdlaqt.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtaciqemuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtiznzxxpa.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtygkuxums.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtejliugoe.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtxypxkaqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtnwevffjo.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtabcpdamx.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtiktedsuh.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtecnddeff.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtjypdjmic.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtptjvshyh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtqlfrryrf.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtojymeoqu.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtbdniisrt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvojpyyba.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtawtdknji.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyvfrymrl.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtvwtipzvd.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtzpwtaxrx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtqjzeybsu.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtgilziqrm.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtbuotmtiw.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtickrzibj.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gthkzhrzun.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtpbkvpvqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtxyckhhdf.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtvixfytkq.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gtyijimgnk.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtpuwwfcni.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtqylqywve.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtmrcuexxg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtuufipvbt.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtkjkqbupa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtlvpchppm.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gthbilmfxd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtkijtfnos.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtzmqaedet.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvegcmdha.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtkoziylpe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtpppvlusl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtqjqqotit.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gthdebzaho.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtbdwwwspm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtdkyzaewp.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtcxupakaa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtasuowquj.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalijnvag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtxloqplsg.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtlckhuepm.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtmznxqpzp.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtrtuehwkb.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtjjuvdvhk.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtkkimkyir.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtmzwktmdy.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxpndqhji.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtvkrckhvf.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtrjopzrnb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gthldsmvkr.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtvsdzagkf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtumeynmfz.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtpfqpucrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtvxioibkx.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtlqcjsjjk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtimpvujsm.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtvlxnobmh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtyxnoyqca.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtammrlbff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtnsuwcldp.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtyztvhmfg.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtchhgzizk.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtlksykfjf.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtdlowhtyh.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtkcwtdtiz.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtnqmpxssh.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gthyrzjzfp.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtmwjgcmke.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtthzgywwc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gtiuyvpjqj.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtiusfnpck.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtkpyhhaol.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtmgdfappo.html

#endif
来源：http://dali.ivvv.top/Article/details/gtcgjywxlg.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gthqwwczlr.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtropsvbmx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtogcahwrs.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtnquoznqm.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtvnqxxctg.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtljgxuovw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtmpewfmkl.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtujbcivah.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gthunqpvwf.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gttdsxqezy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtstaetnju.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtqnijadjy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtpgtlsfzm.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtyvttkbdw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedvncwwk.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtibrrfnnv.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtrvycumxu.html


<!-- 参考信息 -->