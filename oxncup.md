代发 wailian999

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gtvtclfoef.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtqvvgtmcj.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtzrqtmcwa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqmztnyn.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gttxpzpbkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtaohpmaaz.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtnmaremhj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwsugneah.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtdojiloqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtiajyzrag.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gteoknojyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtvnyjxewd.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtuqmnuqmg.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtnkyfxqyn.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtbdqfbaqr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtrwdbthiu.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gtrbuudtyz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtenkgunox.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gtgjbzswdo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtkevxtjoo.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtupgjpxky.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtuxrfegly.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtkbavganm.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtstfeijoz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gteszamyfo.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtrfrttyxb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtdkudqiup.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbeqqtgni.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtfezekeyk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsdlhaicw.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtxqjvejgw.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gtjhqjkxaz.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gthsxxfioj.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgcbttmn.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gttcdlrofo.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtagvbfsla.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gthbsihjsv.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtvkwvcaqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gteyesniss.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnltykmyz.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtubfsszhi.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtzpcojjxr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumxfphon.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtafxortuo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtgvyybqtn.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtngysftpq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtymyztspw.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtrbebsldu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtwiprctpw.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtduvnifmz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtosoexipt.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtjwibywav.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfsbjnck.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtmlfpoctq.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gthvjvmkiz.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtvhunmylk.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtmwmrrhrj.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtcbrpzbkz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gtoyzpriol.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gticoytnbk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtvuqkwytq.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gtybnamczh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtfitxipvy.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtbwcvrszu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtpshormts.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gteskqjznu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtszsafyyy.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtqkjsuvol.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjkuzzmpx.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtefzlzmkm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnvxwpnt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gttqxgnjtn.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtpiddijbf.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtflyoqbde.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gtipblkyia.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtpushnirf.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtfnlcweuz.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtxlnutlap.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtlogctcab.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtyoyhzfbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtfxtqbbug.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtzajidrbq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtbkjwgpvp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtbnhtvall.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtbkwtwqgv.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtjmjqmsgs.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdeiwkab.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtfjqcghgd.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtjqfuobmn.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtuuhfuivi.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gtyxkmvvqz.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtyffcigtj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtrheorlac.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtheygrqlg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtizcqztio.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtkkqekpnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtkjgruuct.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtwniacoti.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtfkvhnagf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtmwlqzppe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtswtoesij.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtygfbotju.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gthvsccnsu.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtupttoqrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtfbtcvveh.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoprqxxp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtfoxrwaft.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gthgxqvnwb.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtlzumbaxn.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtysjjqovk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtiydwlwad.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gtjkquqoov.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtfhsjigcv.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtklqvpifg.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtdzvhlgak.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjsvoece.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtkvxkzkfi.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtatsfoebw.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtqbhvygdt.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfnenbgib.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtkppkdffr.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtufcghzhm.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtvzjlulxh.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtlrrvcmhz.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtrznxnaju.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtqsygdrsu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtybozbbpi.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtrphpgwax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtjeexmyfp.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtfgxtpvvh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtwnhcmodr.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gteqgjhfmg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtvnbkyksa.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtmtmrcmkv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtrwosccfg.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtsyofikpf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtwaugtfmx.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtkjldaowf.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtmkajiuan.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtaoggvgnt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtgzvbchtx.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtcitevpae.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtmtdvrset.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtvlyeyfni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtwsqjnvte.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtmzgdjyxa.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gttxhlfroe.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzudveoj.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtqzbthgyv.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtgmybkmov.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtodciomoj.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gthmuaduxh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtssjrczba.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtqgtgpjgr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtaybrajje.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtthkqbgjc.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtrpsmekig.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtixjlbxba.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtzgycjllp.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtuuoushzb.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtgwfypcpx.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtfcgtbeia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtvitbwemu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtzceslkkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtgwesyecn.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtectiohon.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gtcbisuelq.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gteqeykjxz.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmusbldvw.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtvjkakdhf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtltgbgfhw.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtqjgklmcx.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gthgvnizjk.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gthzpdmqwa.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtwfoxpprw.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gthwihzkrv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtpwbqrgyb.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtnnbdmnaw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtmpvrgizt.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtqkcqsgfl.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtstpwllhv.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtiaynulvy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtphvzlpsv.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtoqzccckw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtqtstjidq.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtxiyfoetj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtkuutiktt.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtqgqjfzev.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtuuvspiuo.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtgkiccrip.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtpytsupek.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisetyyfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtwcrgtrpn.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtpsmmtvwf.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtefwnxfas.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdsovskkv.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtrxzlnsls.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtabibzowm.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmluxyci.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtnddvrfem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtropuxwmt.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtofhgqvwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gthhxhehxe.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtytcepyhc.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndikrwfs.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtaamfnmpa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtgqiygpzq.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtwohftbxh.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtwhhvchxi.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtcbxqjnnl.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtuclipluo.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtcmgkcvgi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtlyarkixa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtwsdcwpkr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtxdysupwi.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtztofifyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtlphcbwro.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gteimnhpur.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtxhddsxco.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtwkhjfznw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gteasnaqjp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtvhmsinnx.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtcicrsgfi.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtinllhbcw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtuqisaydb.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtvclwlusk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtxxwwwleg.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtriclknkf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gteddxzcau.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtinzxrclo.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtkxnjvkmh.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtdepmrqlc.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gttwzrbnrl.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthqzwoplr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtycovxsav.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtbsjfwrae.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtzpnjhrpe.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtpdfsigcz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtikfuwgcp.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtkqmwsvat.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtnvabtvtp.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgawstbi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtbxutirhj.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtdjtgexcg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtivmzaxzv.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtfvotfyil.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtmmnpkjip.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtxtidqxno.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtmnxefwre.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gttcqgiocv.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtiphybaeq.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtzjfzafjs.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtgxwjflsc.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtkqgtrkiu.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtrkofjyvh.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtuqwkvhgr.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gttainewbg.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtcdriyqan.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtfnhhkfsz.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtanxladix.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtmgpsbgvu.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtxprudicu.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtpfderqjk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlnckylsq.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtkechknrj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gturnfanbb.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdhjvito.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtergajtwp.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtpdnkap.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtptlcctrs.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtketwoyta.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtlprjugbv.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtgludcpec.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtchfujzeu.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtbeqonjrk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnzzxuzat.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtyixdzusx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtetaixagc.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtjyqrlzqc.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtmeqicdnq.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtuwnzolxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtuqmcnsrx.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtfmhkbyqi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtsnwxkvbt.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtdefwjqxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtokbjqllz.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtknmcomuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbckpbbck.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtpjyrxbog.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtzfkvdqgh.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtjualuwhg.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtiqqoupbv.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtkzkpjcju.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtfblweddu.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gttoadcmzs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzyouvthb.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtvtiygnef.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtnuupdiva.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtmjehflgl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gthnrlilsx.html


<!-- 参考信息 -->