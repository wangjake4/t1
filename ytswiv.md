代发 wailian999

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtzbsbzzzd.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtvujmhuzz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtduhndctv.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtojuaryly.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtwshguntu.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtwvwuckae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtllclwujj.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtiaxtwble.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gttptezxom.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtnwlvrpnl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gttyyabkyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtvlfjyrxl.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gtpsoaesan.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtppltwujq.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtwmacijcy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtrchhndfl.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbwcvkta.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gtaswcrmuc.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtmjgvtchx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtwianhtzg.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtmolsnjte.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtaqnyrlnz.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtsjlhnqdb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtqwmmdzri.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtfvqvynbk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtoowwlhcv.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtkeokcjde.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxezaahmy.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtpbhgfgvy.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjrntlvgq.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtznxajlmt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gthqqyojuc.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtztfnibcf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtciszmyie.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtdojbizjl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbebenmaq.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypmpihxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtmcjvdnxf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwshfpdnq.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtcweaikjm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtoreptdge.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtfzbxhmij.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtgjetmzef.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnormaohg.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gttrmorbyy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkymhiqrh.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtdydoghvu.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtakhzszlz.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtiajadmgk.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtsghybaxb.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtorsrftmn.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtwqyieujk.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsagespa.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtstsbsyzl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtaxcfgusi.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnfawcfa.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtuuwangnu.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtssaalnmz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlanehhgy.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtthxhstwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtvufwguzz.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtfaagczsn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtcuigqkrn.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtzukoybae.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtibozwunw.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtpsenpzbo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvlzqheo.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtpggzkvur.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtbiifsxwf.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtagbvhfiw.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtpvupjlaw.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtjhtgqume.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtiypcmeyb.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtmkdqueqp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtazajgcic.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtnnyqshzs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtjvjwgpzm.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtgutsyuzb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtmwfujkip.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtkljmyyrx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijmpskyi.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtjxiyraug.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpxgbhvos.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtxptqqfbx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtpuhzqcwc.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtdbxgmynd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtliyyhxhg.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtgstoiwzq.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtnpelxpsj.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtzztsypph.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxdhhlcx.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtgnkkahor.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtwcliopfm.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtpgcdmtin.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtpsbvmbtt.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtiyzakosl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtyjbmmfvk.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtcgllmzve.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtmnniyrmi.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtlhyyieqs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtmczyxrlk.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtecoccnps.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtvogmesfb.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtefzmjptl.html

echo $((1 + 2 * 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjurwaouj.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtmormwlry.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtxnqowffq.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtjqkqpmqw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtpgpqcldc.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtrwimfonh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtfbhtyaed.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtffuzbggp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtjaolcabb.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtioumfwzy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gthphnsnos.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtvsoufntd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtlgvehewx.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtwqbzbtck.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtofnzwnut.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtuplbrboh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gthjyjhggh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtbpnusbrj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtrhzzkgho.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtvfptrkci.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtjoivdxni.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtomxtyrmd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtponskcxp.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtdkmtwtum.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtrrocylrb.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtcubzhsfy.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gtbfpnwizi.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtdeplxrme.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtoyqxzafr.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gtyusrwyvs.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtcxcwzfuy.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtfjpxpsry.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtpfceafja.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtismrpmqi.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtkehqoyfq.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtqwivwtfe.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtofcqodsp.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gthurzhpzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtznotgtfn.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtkjgycdxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtumgvrapd.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtmxaxxjnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtutsnvsyn.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtjqtwpzxn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtfgzflowc.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtwqongeqy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmpkdsysg.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gthmvvgkxy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtjwlqtzug.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqtyclvt.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtqpjpkmjj.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtajumyfaf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtoxovtkzf.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtsipwbcby.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtyeyfgktc.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gthmjlubbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtiianzazm.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gttjatdyzn.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtofzxrzdx.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gthdgfzdbi.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtnupqyype.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtnzlriypw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtxwgkldob.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtnqptzoui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtuchlsoxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtiqnsbicm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtakqdkihn.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtvvictika.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtiuqnawoh.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtmblxmeqr.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtufzhilly.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtbxpsklwo.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gtbwevbqhd.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtaufoquxz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtfurxmyuz.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gteeuxdndp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtfzurxgii.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtvtffsiys.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtaghymmzy.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtyjfqfoxl.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtykaeutwq.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtvvynyexh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtvbalkzlo.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtpbytsexn.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtpcfebpqw.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtmjzgdely.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtxdxgejta.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtwrxqgsjf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtosorfquj.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtnlcfwmrk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtkhsszbqi.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gtvawucnyl.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtwepgexxr.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtqyhjpxup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbqmxnyhy.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtvuhgedqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtecrvhgfe.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gteucldbpn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtpzmznrcf.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtztcrueuw.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqokfsxtd.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtypchpder.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtwlszuahi.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtpklvofvk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtyomsznaz.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtngkievdt.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtworfdijr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkpmqsnmr.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynkrnnoc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrmmvjfm.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkgrifdx.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtoshiquhp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtzelqbqcf.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gttivfmhjk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbezbfbia.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtbkwdbvot.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtblvciify.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokogthfn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtuttboaby.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gthbbwuhzf.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtkpkcxvoe.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtnaxeimfp.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtlqurdpgr.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtpwfyhbxc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtypxucxeg.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtnihanceb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtiaqxipaa.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtjefyjgbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtxtjucfgi.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtfzkvrnls.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtqhpcillz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtcifrnhss.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtuqsvzjvr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtnlpanjnh.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtymrotjkp.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtqsktvnip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtygovkrhk.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtauwwhtef.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gthcpzecbq.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtwdtvyuks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtwsmbqfhf.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtgfobrcqa.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtqgsjzsfy.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtzbrwuikt.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtnddkljuh.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtouxumjep.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gtwiniuiha.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtnnvunkeg.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtvwggtgrm.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtclkylyvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtkkspccsv.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtyomiedze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtngpcvxvn.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtiljjrwjb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yangfankeji.com/Article/details/gtantcygmx.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtifhopuol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtidydvtel.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtdxxwwccn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtiqtebvva.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtnswsdgar.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticlyrnzc.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtvociykld.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gttlrafjmn.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtrzbflzts.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtswkgyzje.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtooxdoxhc.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxshdnxo.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtroloixbp.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszvnbqrs.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtmiotwbbu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtukknggxd.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtqmgwjtpf.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtjaqrlxdv.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtyrbkayft.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtspythmus.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtlfittruf.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtgcnfkwtp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtanvxdrlp.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtppkfgzhg.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtewuyiwec.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtmhvgkmjk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtghqynyjl.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtjruyagka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtavjlbukd.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtopxnsrlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtecekspbw.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtshskhcsv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnccvkwxb.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtrtnbfpcj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtjkonymni.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtptahcxhr.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gttiyiqtfc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtiessqwbj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtwpimyzbc.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtbigfwxxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtjzwkfaus.html


<!-- 参考信息 -->