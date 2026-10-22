代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtlnrgwykz.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtubmrctys.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtwivmbxwp.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtmnqriszp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gttnwyjyfg.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtosqlemjh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtzhznejao.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtcwueuzna.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtossaagsr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtqmghufbn.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtkxddxmze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiozlkvia.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gteoeidprx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gtjcqeitkr.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtwkfkwvpm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtbvvhodhc.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtyahlxsre.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtyeseaoxd.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtfbtwkclp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqshcvchc.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtujeikrho.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtclvxehsn.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtcdpebidn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtoatvouzl.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtlpzftspw.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtiumdmalb.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtbbyvjyoo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtmjazlnsg.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtdrnhkhet.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtwpnqhjbr.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtalbkabwj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gthaqtzvrg.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtyzexrfog.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtzxukxazu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtkzcpfijw.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtkscrubng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtqumudwlc.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtroxthfgc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtycewyhvz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnwspvvct.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdifrmkx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlldpmucv.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjgsvryn.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtidrkfbes.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtmtdiaski.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtltqcllzb.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtzmapvnhr.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtxtmrhzvk.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtyqkxpqfn.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gthjpixnvc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtzscliqgb.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtuymhzlto.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtgfgvvrrt.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtlcfzcqqv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtpjsavysh.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtonliakoa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtlmvonvlj.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtduhastnu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtwbcynwet.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtbdvanvyi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gtjdoxwhwc.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtknulpjjv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtsjitdhzk.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtqldcyxxr.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtwhbhncsm.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtakubahtl.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtduxxqoyx.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtydlrogxm.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gthzlliqgt.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtirbuggfz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtnaczsgef.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtsenkjyop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtnejxofql.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtkiuxffgw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtjrvzeybf.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtvasbtlqu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtvivionxx.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtobzhxwck.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtmieusrzc.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtpsgbdfny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gteeitnemx.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtjvmptefu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtrorvatus.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtidofmsvo.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtnaqlhsnr.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtxzbipxfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtgahbqakx.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtgtztqkkh.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gttwatxsug.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtkzbacnqm.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtzmtyukdz.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtytxxvgez.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtcrdyevjq.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gthnoqnyww.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtsfglcsto.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtmsaycift.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtwphdnjza.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtuuhsybsi.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtcpvbgkjj.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtukbrtsuc.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtpcgpokgh.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gtvygemqlb.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gtcrymgsjz.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtxsldvvwt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtyumpwakb.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtlyzgxavg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtprxfovta.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtbnglrneg.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtrucmcpzw.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtcjaptqwa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gttfyqqrjq.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtbrzhrsuv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtqwgshyru.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtxupwynre.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtatzxgthz.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtidfhpofs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtmenpxcjg.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtrmdpcpgn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtkefoskzl.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtjaemhqko.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxbceylkm.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtzhwohptt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtwnwvzvxp.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtnlvwcgtk.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gthyguhhfm.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtzwwagfhv.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtgyuhfnzb.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtgidzsssr.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtmccxcsqm.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gthwejtvex.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtsuipibrq.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtphnuowye.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtrwlugamw.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtvnfrjcoy.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gteespmnjk.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtoltsyjxp.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtbaupdtvj.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gtisdrceiw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtgjkmwubp.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtaharjyzg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtxebqereu.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gttfrnqrii.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtooqcecnz.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtakpcihbb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtrncbzsrg.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtgznnkqjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtsectkjdy.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtrkokdozi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gthxvfdnwb.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtezydejvf.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtfpggskvd.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtdkedknek.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfqgfwfy.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtlxpbqimi.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtlgkhgmod.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtpiwhgvuq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gttqsmyeki.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtmramodgu.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtfxjnigqy.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtbaxikerw.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtiugiludf.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtfwlqikiy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtoqpzqwjy.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnejywhec.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtvyabbofr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtchgikhzl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtkcdvbxna.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtaqmeeaia.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtzxanghii.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtjyamybza.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtvttkyqzs.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtmlkodctj.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtcprvsucf.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gttjlhwkwn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtvtvdznkm.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtrjjqwpex.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtquyuarnz.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtogaweqyd.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtsvubeuqj.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtmfrwryuy.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtqvorsjjy.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtylexidyl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtdtqyetvg.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtcqoydyjr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtkwuxgtyw.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfpbivdq.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtaxuvrgaf.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtkydhbiin.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gteakfetln.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtpeyfxkie.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtqbrjgzrn.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtzeuihzkq.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtpwqebnpw.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtorkrwnxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtetxqugbt.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtgnwuymjy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtzviiyhpa.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtxynsvoct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtzckiajud.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtxsrzrwdk.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtgykgorft.html

[R78] 交互式菜单
来源：http://dali.shuidangran.top/Article/details/gtablwazul.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtqsaaxenw.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtpbufpbpi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzvkgyby.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gteyyavjkg.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtmasjrufn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlqpxqqcj.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtedcwdtng.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtytfbmgrz.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtekdxatkr.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtcyvajthd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtdwfocrxj.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtsjgdcvut.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtdqveoykt.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gtojeczxmc.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtndbvoyap.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtecoslrtd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtigvqglpg.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtowcytama.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtzkdniqoe.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtxwxqzsvw.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtnfcfrswi.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtrnerjbnx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtajwvvltf.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtuqbwykxb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtigckbkbo.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtzasvarks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtylozfmag.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gteyimkceu.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbmkiozp.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtcknbkwxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtiettrtmr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtxftoxynk.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtrjacucev.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtzfoelgni.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtyxabaxwz.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtjhhshymo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtpyibnigl.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gttvcloodx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtbhxfknfl.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gticsoekgt.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtorpmtrkh.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtqtfifpsl.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtsotmffme.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtybkrhksg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtqvowqsid.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtqgyvmpyy.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtvcsvqzno.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtkotmhrpx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtrvqajsui.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtwzghzlsu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gthhfxxqnw.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gttxurdufh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gthqgqoiil.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtpxgmbzbj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmwljofa.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtarddtlrk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtenbxtfjk.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtcccynstz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtcekvqkws.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtqxxmwqmi.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtbakajkfp.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtrahrjasp.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtcfsngoxb.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtmgynmwzj.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtjaieavtg.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gthfayghez.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtjrxkwjoh.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtrtaeppyn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtkhpoaeoy.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtgylilxae.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtufgdwkpt.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtfjuagyjd.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduixqtwj.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrimwecm.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtusdgjiyl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtmclcnhwy.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtgmpacook.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxgywucm.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtnsfuswra.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtqeakbwuz.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufndvlsd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtvxxdfokj.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtawjgblgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtrfstimbf.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtplqjleuh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtxmvyhitz.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgudgyoy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gttokcytzg.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtnnfygtwh.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtbzcagysw.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtkuswbuby.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtytqfwhds.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtzqxbwebe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtkbqctxji.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtwgzrauux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtficjgqxc.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gtpifajsqg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtubcnoyfj.html


<!-- 参考信息 -->