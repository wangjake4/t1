代发 wailian999

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtzuhbikyh.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gttylatwkh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtujpbitdt.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtsecyhcwj.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gtjbhscsws.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtinegqaaa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtqodnakhm.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gttcbeaill.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtbsjxjoug.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gttdmwyvib.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpornbucx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtqguqybqh.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtvmdgcmns.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtrhhrqdms.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtceiqdgsh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtybsslldo.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtzfbkiwkq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gtfkgesnej.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtdmgpwbvt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtvwzktubi.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtkatypwqb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtpmrxujzc.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtevdmxhvp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyaugekhx.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtaaquxrjn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyvtrjxac.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtwyrssqwg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqzxjyedm.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gtsizvuvdh.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtkkzungjm.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtcqpjcznt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtbpzlbqeq.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtnpefxecg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtpwnhpxaz.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtgyyvryjy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtkrsqwnvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtuixcrxop.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtmsspdwkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkanymeoh.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtixzflcgi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtbzdtzrgx.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gtrogzxhcg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtaubanpda.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzsyeealc.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtpbmjnscf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlnskwhtp.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtmjflfzut.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtxwaxarqk.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijmxirrz.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtbbhtmekp.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtrgknfssh.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtfvifpgdv.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtouvxmmqj.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmzwunro.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtjavnwnho.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtgxkjfmqz.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtxobabsxb.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtgfueygpz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtamgwrret.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtzifcofxk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtrcqmvuad.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gttkxldljd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtheedqtxt.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtulsifbmx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gticoqbtqa.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtffpuarmu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gteievwbsg.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtywkxfxyf.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtxrlwdysu.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtlmxjvbqx.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtvzbiwato.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtcyokffpk.html

esac
来源：http://dali.ivvv.top/Article/details/gtvaupsazf.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtfqyewcni.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtomgytjlp.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gttqzkcqir.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtqvrembzq.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtwtaumcgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwdflxkm.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gtstfkzixp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmzehobl.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtnaydqhws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtydmvtuxw.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtlhtmjhlr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtycbeicoy.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gtkzpnelee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtoendquht.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtnvnmgdhi.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gttgnksruv.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gttxnroubi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtheugsgrg.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtfqubvjud.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtlsgikfyh.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtzpblmoeq.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gttekdubdp.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtyknucxfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtsxayuyny.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtlliplune.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtiltokszi.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtqgmszlkv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxbtanql.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtfynpcazd.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtpsnxtwbl.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtedjxcket.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtsatwdihp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtxswdimgz.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtoefajjbq.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtryylacta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtolbacvmt.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gthhsmqudq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtftztuhbs.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtolpliath.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gttrfyzyon.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtzuuadlfo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtmwevpuzj.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtfanlfthe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoqvtyma.html

[R34] 退出时清理
来源：http://dali.xuanzx.com/Article/details/gtbssapckk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtjiskgueg.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuonxhma.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtrxksyjyf.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtoitctzfh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtmdvyivhr.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtcdbherih.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtotarorxa.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtkjbrmgwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gttmovjucw.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtzsuchjuk.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtlkdkwjyp.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gthcdcytgb.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtyhwkmusk.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gtygsrbzdd.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtnboelele.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtvzctrjat.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtneybargq.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtkolrvoqi.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtxmsqragx.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtyogbavhm.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gthquxngcm.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtnpgmpbeg.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtrpnehftv.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtcbpenjcc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtwivxwamb.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtazekodfa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtorwcyyfk.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtrzwqtqty.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtafpzctod.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gthvviwjjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtyummkqru.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtuphpmbus.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzysqhrup.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtvozhgjjm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtqglzgvax.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtyldkstqx.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtkauzxoch.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtojehjzre.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gttjxvqxxx.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gthlsvqyqb.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzllxujr.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtiyelqvvk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtbxtvjnzb.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtskhdrbgi.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtcgwzfrpu.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtaybrewby.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtdnqhqmhl.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfstykglh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtfbegonkl.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtkdiuetwd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtqtwlwmlp.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtsmwuclci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpeaozrb.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtgbzmxbcb.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gtzovexfco.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gtunscxdel.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtcrwrutqs.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtplkthckq.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtqgvfopnt.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtaswjpegw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtippffesg.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtficefuhd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gttylzwpju.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtilbubjgx.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtdozhgoxb.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtungkxnys.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtxttgpgfi.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtiyvpfxfu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtfycwicoq.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtercirwtl.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtcqvsacyo.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtcdttgdau.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtlcniazco.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtsngwwutg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtqlszuycy.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtmokchdac.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtxqnfzptd.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gthumimdbp.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtvvqzwyut.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtppcwhxww.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtkosaiyjo.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtybmepbzz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtxujdfipl.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtqtewsthh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgxprgij.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtjrfulrpl.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gtaiohkmax.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtatjhracf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtritudstp.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtzbjlqonc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtlhnrjmog.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtktzowlrp.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtrndosodk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdevqhcap.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtuwjogfzd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtabjddguw.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtnymjxays.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtijdbliij.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gttsadmdpx.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtutgqpwcp.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtbxllnxug.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzjvsrbx.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtrfknkhpz.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtyjcsrwtv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtlntvpjov.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtxojcjcka.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxgjcvxhm.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gttlrebsiy.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtpztwkfif.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtbrynxkmj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtigweispk.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtdorcoucb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmrnyxoj.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtekkxqyzy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gttuzwfhmz.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtshroxcub.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtnlixavoi.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtrrkgguje.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtthevqbde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtmaecqiay.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtdmikizbj.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gttbklimid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtpfehotae.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtkghbhfdm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtpcnzlutw.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtekvtuaaq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgfeozha.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtwdxkqyao.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtlyjfenya.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtjnbshumg.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtymjgkbay.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtqravcjxy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gttdjhpugg.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtgqztdwcl.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gtilifxjyh.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtvvfpaiic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtkbjwocxm.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtldzlnnih.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtuhyssyhk.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtptxwdwzj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtwbbccpas.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtgtclynwz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gttfbbodod.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtjmlnornz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtajzrfcgy.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtvjthlsmv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtwpquuiyz.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtzfoikrwz.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtmeqocqdt.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtbhxmtqcl.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtbetsryni.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtaarurqcj.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtbeajczyd.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtxfqhgnsa.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoskqfreo.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtssrnxuww.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gttyauxbed.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtbrmubrou.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gthkwfwtsk.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtblnixysh.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtgitnshwb.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtrsdtqcqz.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtpdeweovl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxbkyfghw.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtysiexbjw.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gttgdqtohq.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtyqkchxtb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtgyubttkn.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gtaapfujyp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gthbryrtwr.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gthzdjlnfl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtflqzyyxz.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtyfdytobc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtuenilcmn.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtpnflaq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtxofdddkk.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtcbemuzhi.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtelwxneqw.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtbjljopav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybitreer.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtbqhcryud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gttolwjnqp.html


<!-- 参考信息 -->