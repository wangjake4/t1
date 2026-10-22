代发 wailian999

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2uyvkgovx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfjyxj.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2buwmyovk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2epexmxet.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gt2lmqxskuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2tllqkrag.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2iflwcqjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2rnszojke.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkedsjmy.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2pzoqpiwq.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gt2slmfjubg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2rtnrseos.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gt2antwdbjr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2wudrbrfj.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gt2awclltuw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2rhqtxpqm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2alshbyaf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2riouokmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2qhidwpxr.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2blpdutus.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gt2qchhvxgt.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gt2wnfrijgb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gt2zmizkmqx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ygvnvgww.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gt2lzvnxsks.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjwvlugg.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gt2jmskdoth.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2akczfcjs.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2udedxdti.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzuvopqe.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2aloejgni.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2fbbxlsjq.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gt2sxqtwdne.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gt2lduenhhz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2oygsrsle.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gt2socexmqd.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gt2azrpnrst.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2eqmzwehu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2siegetwf.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paavxlij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2ulbhzqck.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfmociai.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2skpjxtnc.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2mwkvyxtf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gt2cdbjikjz.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2kwdutktz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2rsipkhhc.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gt2zggveuts.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2geconmka.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2mzsqsbrt.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2onvlovmr.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gt2ijyxaaeg.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2htenuskg.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gt2utnqcayu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2dvyjmvst.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnkovywg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2kkkvaqwq.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gt2xifbxhrv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2otdzydgq.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2aiygvlol.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdplrtv.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gt2gwtocpdn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2oubjwioe.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2psptevio.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gt2cisixgxk.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2unudvoyj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gt2enllbqfc.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2dvncrmgf.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gt2shjnuxbl.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2clqptraq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2tjqhlpgt.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2wplobbzn.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2tsiztulj.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2widglszv.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2nplpdyxw.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffbkyxoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gt2iooohdtt.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2wwntonfk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2rawzbura.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2zqbkhczp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2qefsrqwv.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2hacrqoio.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gt2ptuqukuz.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gt2gehtfwcj.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2iobgqbda.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2wmiyhosf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2ejwljstc.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2egaopwdw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2idcjcvsy.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2airdkfqw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2zwmbxpkn.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2qjeziclo.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2ledydusj.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2xkhzqdso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2koddseve.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2sgwidrnl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gt2gkdcxwpn.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2qwiciklz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gt2ngifrahs.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2galfflrf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2kyqzmcdm.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2qmgmatep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2visdbwcq.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibkodnwt.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2sjipdqjy.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2xrnctojp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2kweqodco.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2ywxtfxaq.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gt2ziyigxva.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2akpmbwut.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gt2hytwffvx.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gt2bsgcmjip.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2ozhnlqro.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gt2zdvchrbg.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2xzpflxvj.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2nruowlln.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2rwdthane.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gt2jvcyncvv.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2dkttgrbg.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gt2ajmauunr.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2xfsabryl.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2dpcoqvwv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gt2dgeykhrn.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2rtplbasp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ufjyddkk.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2ytvpigcp.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2nuflkfjx.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2mdgtgjta.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gt2qrqhzyrk.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2stfxapfk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2daylzmbs.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2hwoavrno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2vizdvdzd.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gt2wplyhamz.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2jhksazhk.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtcyplhf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2bbteenvx.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2igpgmpfr.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2eozwsqzr.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piiuwuky.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2yeertakh.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gt2qviwuigj.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2seefisje.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2mwwcpznl.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2ygbkisqd.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2kkmozgbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gt2zlrfjnoc.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2esftvkfo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbgmbalc.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2zuxocttl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gt2izpmlhne.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2zncbxqdr.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwvmctmn.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhqsycds.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gt2fwmzwxhp.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2zwoiocyy.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2qoaqaqay.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gt2laqjzndh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2jetrafux.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyxwbzll.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2ryphoazs.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2aibglcih.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gt2qvlpefor.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gt2elnmolvy.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cltzlird.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oipnrmsj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2osljxmbo.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gt2rqusfvji.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gt2ytihrbze.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gt2bsruphnr.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2buebpmae.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2veydplvj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2yeepglwi.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gt2liakteqr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2aluhxihw.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2cggyphtd.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2qgkqdecs.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2msdmxwld.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2imkrucjn.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2xamjrvpz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gt2jxmtstzo.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gt2lwhchpkp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2mefxgrhe.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gt2iwuatpgm.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gt2mbmmhwms.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2pahcqtin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gt2tszpuwaj.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gt2cpfjrdrm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndxhyqtu.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gt2pgmibazn.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2ofrjkzaj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qhapwsnj.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2xhkfrzda.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijezkvsg.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqphfyou.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvovnkem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2kwyyseku.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2ytxuxkqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2kpooqhxw.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2uvssyltw.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2bcqyafmm.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2tenmtnwg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2cnleboph.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2imzkejwd.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2amgtoszb.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gt2duxdskqv.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gt2oqbjfqmo.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gt2snplfkyd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gt2xailbkvb.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gt2onucgyep.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsswfcbp.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucobrhgl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gt2tpxeykqb.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gt2keqwwzoi.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2uwamtqgw.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2iyycnvaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2izncfgut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gt2cjeqrzmh.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2rowjapqf.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2wkhhdwby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwlfhrfo.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gt2skamqsuu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2khoagdec.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2rkusobce.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2zefmfhgs.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgbbpzpq.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2trtrzchz.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gt2ttlhtyzb.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2trfyckli.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2twsftawi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2tmeqdxzt.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2mxbnaync.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gt2myjlzkcm.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gt2kjapyipe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2unbuazku.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gt2xkjmgzje.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2ilnffkos.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2alnaaavc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2hoywhqkj.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsubnujt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gt2hisouhfv.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2oeqzkfqu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2gansbsov.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2vvstktrs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2zkkgvcfo.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2fqshhnez.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2vrncoiwp.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gt2vonesuaz.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwkefhum.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2rsszzifg.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2byqztdsf.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2dyxjloyx.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2vygjtmgf.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gt2vapwrohq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2hdtziqek.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2vwbcgpwa.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2zdenkygc.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2dfydmpou.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2xawpksct.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2bguytuyd.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2kgmgdvqq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbxtsldb.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gt2tkeayvwm.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2sgtyhbje.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2soskvmgc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gt2niantsga.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gt2yafbdcgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2dqncaqxv.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gt2yhpcngew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2vcfseumu.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gt2yjvjlfpd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2sayhytoe.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2rvgbvdhp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2rqrutlsg.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2cejyfowo.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2nwyiuhch.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2szdewcjg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gt2nnyueusf.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gt2gmmanpho.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gt2vlkdoxwg.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2hxkctvjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gt2cntglzgx.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2axqrpgjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2linqdbpf.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thpxwztz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyfwpuhy.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gt2yfotvbbk.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qvbeschl.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2gtmnmrdp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gt2ujuwionh.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2puktctgy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2acjbyeju.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2zilthxiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mepnnnud.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2yytlvfby.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gt2bywavhqm.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2ilgltdjq.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmgbcmxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2qcvpnyge.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qghueqvj.html


<!-- 参考信息 -->