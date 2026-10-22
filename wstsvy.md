代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2aetqtzom.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gt2wpieagjx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2sxolueiz.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2ykjvjpsx.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2wmvzmoja.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2dhlytxev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2zzlywvza.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2kpjjqujd.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2qutmilii.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gt2undhkaur.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2rmmvwifz.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2aufuctkh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gt2pdnpbaug.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2utbozpvw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2zdqqylfl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcqwoctq.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gt2etlnoqma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2yyvripmw.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2vndphhtu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gt2agftqglx.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2pdqtiwop.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2zsjkomje.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2ryyutefn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gt2hrvglrbg.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gt2zkstpaqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2iccwyqki.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2pvtbrras.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2nmidkiru.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gt2fzifpavc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2spvuxzfh.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2dyjvvjuk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2afnqvtvy.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2hkrqjxhy.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2sinflqps.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gt2zpofuktu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2zvyaorkk.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gt2mzadeotm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gt2ujdckviw.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugxikass.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gt2howaryiw.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gt2wlblyywq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gt2eoywxjnn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ylptspga.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdojhbbb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2lgthmetd.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gt2bkozbkba.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2owbnwkfc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ndrqalsu.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2rqmcyhio.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2njmjmamg.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2ewkrawbu.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gt2uovvuypr.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asopvfsy.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlxcxouy.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gt2tjqhshjp.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2kcyeustp.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2milzortt.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozwpczlg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gt2teofdafi.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwzrppkw.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gt2pnhfitql.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2ibxlyvuo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2nhguoynq.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2npwrjuva.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gt2whaqxcie.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2dhhafotj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtrenpcm.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyvhvsxg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gt2dbqqtxbc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rtktfdek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iarfulol.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmmpffpt.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gt2qhxwzmfy.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2bfmjhhbs.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2gqcixsaf.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2utcxwhcx.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2qfoqxvzd.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2pxignmgc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2vauayzwi.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2cshawcpj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2lkjaztnv.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gt2msdhktsj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwnrfrwr.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2nqnemgiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2xhqmnilc.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gt2ewvxokqw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2erbktfxp.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2cspttiai.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gt2vmltpaql.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gt2hbbhjyey.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2ihgpphhe.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2fsjmjlyp.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gt2vuzkroga.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzynuvpi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2swsknzen.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2izotzvlq.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gt2hqshjqkc.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2oadkbltw.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2mqqxrwge.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbwrkuu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gt2spcqqofz.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2jqltpcee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2wllqrvrn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2sokhafkk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gt2xqduqlom.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2zjfgkysl.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gt2vgbonxjk.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2eyykixrz.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gt2egcoxdud.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2lkekbzcs.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gt2irbgdrpi.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2aquczjay.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2gcxjycce.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gt2zdrmrlai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2ojqeyvad.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2egravsnx.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2imsfuhza.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2cepundon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2tsbeqieh.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2asbnlbyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2xceymqkx.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2bwsqukow.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2bsjephrq.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gt2kxewxjdh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2tsczwfzg.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gt2tbuaflsf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2jnjyohed.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gt2xtdbodos.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gt2ncjuzruq.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2xipuwpfa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtyrqxkw.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2hcsuhnkb.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvauzvpt.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2sshinbhg.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gt2jzlhgnyp.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2dvtympjg.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2xvkildlu.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gt2zpkcpdyg.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2vopgaxor.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2hyohckzk.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhsmaakk.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2ylzcpejs.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gt2lfznbwnl.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gt2tkoukuoq.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gt2xvxslxbj.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2kbvzlmfo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hljgctsg.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2ozcnsmwk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiqafyww.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywjtryyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2yuzflefr.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2vcurotcq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gt2zdkczhwz.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2vzfqbwzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2giqrecrv.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gt2awjwyryd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gt2xbruvsun.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2guyjhhgq.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2jlastooz.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gt2erjktygh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2mabdrvbs.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gt2grcgaykf.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2nyhtagik.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfwentjt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gt2gaibhffw.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gt2ciuicksm.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gt2qzxnfnvh.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2rlbioivj.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2jffpdwpo.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2uwgtnopw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2awqmbgda.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2rpobcizy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2zjhijjca.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2aiumzqsk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2cgqdturg.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2etlexxii.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfbpippm.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gt2katktigo.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2drhjtaph.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gt2qqxyfsux.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2lhwoexhc.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2rwhmclmk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2dkfrpmtv.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2iaggxwyu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpqyhgbp.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2urckbnbe.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gt2pbipkejh.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2wpbfpjui.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2pamlarrl.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2kaqkzynx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gt2pounviqv.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahcqodwd.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2qxhxuneu.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2puninlgr.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2mhbhdgbf.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2kajoffna.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2gltruuix.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2azelpwwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2xbyijyss.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gt2lrgkkidj.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2rumitpum.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezkpnrtw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2tuxbjgwd.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2jpulnnxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjyslnau.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2vrudxsro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2ziyufqtj.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2ohnqpmnc.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2digoixug.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gt2tutyyzys.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gt2buqivmgj.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gt2vellzfzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2vqyrljdc.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gt2diimgfhd.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gt2gyucvpqp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pmubpjso.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gt2pwwfarke.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ownkmzhn.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2bgzvyoco.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2eagwfokd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2xjekjhqf.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovtzjbso.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gt2btzuvhue.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gt2lskcvcbc.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2btewiemr.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2falsyutj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2rtbbrfxj.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2puumuvgx.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2sauhrtxc.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2ndeoulhx.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2tvmimqcz.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keoddhiq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2omuoyiya.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gt2dlxkvluh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2uwrihlaa.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2dmvurpei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2ixdpyjvs.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gt2rwcjcxud.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gt2uqwzkgod.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2aahnewho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2ubjzbysm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2hclhrmxn.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2ovvobavl.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gt2hftvvlqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2fidmvtdx.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2ooguwzwo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gt2ajlcqryn.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gt2zywlhmeq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzbkhayb.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2wehrhmtt.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2fjperkbo.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2mwublllz.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gt2llvotasx.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2dddzdkgw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2vxallgnr.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2jydhhueb.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2usblpsvl.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2hyaxtjui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2xrducnfh.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gt2dmndzbhp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2alsdwjfe.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gt2qvoypnle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gt2eybqazkz.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2dubjamry.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2btmoasep.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvxjivqh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2pvohkbkj.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gt2mdlhjltu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2htuloyox.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2ckmxqgaf.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2hcdzqrdx.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gt2fkbtxatv.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zthtligp.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2adprrwdz.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2gkbzyegg.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmwgethv.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gt2hqywvxun.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nitwuprx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2cexwoqez.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gt2skumpxte.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2zhjuwuex.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuxsgwry.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2hlumwozk.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbddfojp.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2ypbgyvjb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2ftjgwsey.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gt2gxosvbdc.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxjzfoef.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2nwndqewb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2knkcbizx.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2dgowaomc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2isuhrgmm.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2nfzdwvsn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2ytugpqma.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2crowicwr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2dhjkmnvb.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2djduinvl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2wtvsezjf.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gt2smydqvir.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2qhfgzpbq.html


<!-- 参考信息 -->