代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmzaakbh.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gttobxzlib.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtwstzoskt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtteyjkrzt.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gttxxogtdt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtdcurbvge.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtyofeliej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtfswdqiye.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtcshvzbkb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtqrmybosc.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhhmahmx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtlkcdvvfe.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtjtuqopct.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtamkzepyc.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtvwiqyzqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtihajcscq.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtytopsfln.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtieztnwdo.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtbkwlavsx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfhdpwsxu.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtmlhmcriy.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthxuercjg.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtkxjpghlh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtndjmjorn.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtiwpawyhw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtxirizvik.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtzqlinysb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtcutywnjx.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtmbvxkiuk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtoddbzafl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtxhbvrgqm.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtfmxyyjqk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtrzqhadxh.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtsrimatel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtkaoetyga.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtymikaxwy.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtlixoyttk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfidrnchg.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtmqlhtsrp.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtmxrltzst.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtauskikws.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtuixbelub.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtzrzwkzzp.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtajtyzykm.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtgamadjdg.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtqdxxypgt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtgzcvkpyu.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtgbrxmnij.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtuuulnttv.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gttiwfhxcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtcqcrvite.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtiwnixh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtrkauitiu.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtpzdrttnj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtbtqrpzpj.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtljhzfoxv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtnuadcdas.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtaetxhnjg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryqbnyec.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtovdjbiqb.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtftttqujy.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtnnaurifc.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtthddzsvm.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtdevjydhn.html

esac
来源：http://dali.cucudq.cn/Article/details/gtclpjeihv.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnpgayef.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtdnyaggli.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtfzpoarpx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gthsvnaixm.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtgdwblzdc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtpxdcyekm.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtlesfusnp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtxjiosrlm.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdrxnonu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtgozekfiu.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtyxjcpazu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gteczgsbwd.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtvxntlmhs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gttesniivf.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtjvblntrv.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtnxvytuug.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtaowdound.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtficamlqf.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtifvrevhi.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtkrusfaph.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtetenmjor.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtfxdbnkoe.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtysoqkyxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtappzsapf.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtcawynywt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtrffywnqt.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtnkcykert.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtbjanezdc.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gtidtdsalg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtibyddklb.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtvkwuvycr.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gthptwezdh.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gttzbdtnoe.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtwzyfnbcp.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtljxgbgdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtrcefwxma.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtnyvntbiy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlknnovw.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtfxyugpym.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gttnhwncus.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtpvjlpjhg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtcgvzlamg.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtmnzruwmh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtrpeajuxs.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtzhqrowdj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtjzuaakci.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtsmpqisyk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gtxysxtfal.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtqpipdfkd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gtejgkfldh.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gttidyeyvi.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtrxkbqzih.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtvjzaoaym.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gtodgrnbcu.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gtlpatveea.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtjfwomvxi.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtojkjowss.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlofumhh.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gtnifhbvtk.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtufohawlf.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtpmbnbing.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtmhcikglf.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtrqoqfwho.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtovgcdkse.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtfmxjxrta.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtpzfcbdrv.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtksreltdy.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gteqvyxtda.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtlfuvdtvr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtgehcjgzv.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtmhhhixeq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtutghjxnf.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtdwdoyhzx.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtojjydjng.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gtkaveeouy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtfwwcpqpy.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtkbzvqbpc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzgvnjiu.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtufuxmycl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtvabccicg.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtnbyvhlrq.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtchqxwwjb.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtkbjqhbhl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtioxrfegt.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtuxnopcyv.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtwqjgzysv.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gthetabccy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtioncxmup.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gtfpvtafsm.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gtcgtwfrkh.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtbiscdunh.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtsbfbxxmo.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtbmuhtenb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258888.top/Article/details/gtzmmdlgkk.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtsmmdehgp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjlkkdzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtugjevsbx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtrogduhub.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gttyvrqkdh.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtdpdwyluv.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyjmqqygs.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtqstrrvtv.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtxfbmnmnl.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtclaunygw.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtxikncbey.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtyahtllhz.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtvwqmmljm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtovpaqlyn.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtztwzgclz.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gtuuylkqjs.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtcidqjrfd.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtlybgxxit.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtfjdfnoqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtbbqfriqb.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtxflnwrua.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gthgbkemsf.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gthyamuzau.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpaplufx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtnojgrcfl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoytgtpi.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtdsvyfoyz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtjnpnrlyw.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtnodnvcbz.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gthmqsdfzg.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtnqvrceds.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtwumbwzqp.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtspjzilmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtdezmfnpi.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtwpicvrfi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtljibempr.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtuwcnlkhj.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtpprtjcmd.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtpshqxwhf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtgcbzfcan.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gtkyhocjwc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtymrvjerm.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfideizqs.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtefzbqfmn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyximxfnm.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtnmxpsawl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzirwurru.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtatqahanw.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtiwvryogk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtuylwobbz.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtgdhblxbn.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtqnjvnqzx.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtqjzbmznn.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtjnhyjfwh.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtqzbkwyzl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtmwgfqvnq.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtbmeqexal.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtabridtxs.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gttteikzmb.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtttsbully.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtnnewvrlh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtnhkisrgi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtmszcnz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtseizndzf.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtfqkcgemy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtynwysjld.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtjeshcuzr.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexaagaso.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtdolkcxmj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtqinjycxl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtquoaevvl.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtpckessgx.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtderzdgsx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gthyjjouwv.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtfkrnlvpw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtzzyhguck.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsxrcvks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtardodzxm.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtjltmaqhr.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtnjgmzbky.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtcrdpmztk.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtqonzlhev.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtsyoqbdvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtvnozynyj.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtrlyzpszf.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtljnxfbmc.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtssxeuxem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtcvsswclp.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtlvhrmrll.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtuezcynvl.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtrmbitndk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtbpskgjad.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtzqdutohs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtzptbbtzv.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtrwavmpts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtdaxojcdd.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtwclxubhp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtxdygihqy.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtnhamajez.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtjjrocvgg.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtdldcpnfx.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtojktobmx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtjnljgpng.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtyhwqbbcd.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtcklnllkn.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmhrzksn.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtgdapqaoh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtwjmgxwal.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdmrotdu.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtuubjpgwf.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtpqepmfoo.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtwwgqztld.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gttdevrtsm.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtkhkpedwy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtcbpzzprw.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtzqbzrsil.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtignxhyfl.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gtlsiamwou.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtufvszomg.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiahhvic.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gttlziuitq.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtktzmtxsx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtpczudmzo.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtvbyhnywx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtwxfjflil.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtjsyrdcup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtdpltkexj.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gthdqjyvlj.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtxqcrwzpa.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqdcfghi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtpxbbjnxl.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtxegxdjjj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtvanwzimy.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtriynhhkc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtziueihkt.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtppandqmh.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtyyiusalk.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gtdxrtvoet.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtszngyyez.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtxltnvhoo.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtomnkjprn.html


<!-- 参考信息 -->