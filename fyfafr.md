代发 wailian999

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2cvwwhmgr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajnuqkeq.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2qdhavnjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksclxvla.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2rgujxunm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2mnjurlst.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2msjlobnc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2ezmujhon.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gt2qciwzapj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2rrehaais.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2tuoeutzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkzhqxyq.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2hkyjntvp.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2udahgghi.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2zkxcpkxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gt2adfaoujo.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2idzzhfzj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvjmzsf.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2ytkuwnwz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2kqoqrtct.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gt2mrsnzoix.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2wablilyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2uzywmawx.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2uftfwkak.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2qbgkwefw.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2ssfldfst.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gt2jfgxhbda.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpmypose.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gt2otvwimoo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2psdwgfnp.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2lzrenpro.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2zieofbds.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2bjtbamfn.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbipxuob.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2jfuoatzj.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2qgdsrokg.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gt2uwudarhi.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2uowoikir.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gt2alsyespg.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2juludboy.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2sdrfghge.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2nfkovicu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2vefkrukh.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gt2heqegpoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2qdglbewg.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2ywuuvcqm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2lnhopojm.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnfgwerh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gt2qlimmnai.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkiaswkn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2upychjuf.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2olhajvkl.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkqpsgnx.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2ggndudxd.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2amduwtrc.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2amizsmgo.html

esac
来源：http://dali.mhx1999.top/Article/details/gt2xfqianqj.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzakwgve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2riomaaxb.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2jdabnclq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2jwbdhonr.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvbqxlxl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2kwvwjkkj.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2ucdpgejz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cazkejdt.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2doqmvluv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2phgkhaxi.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gt2baxofygr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2skaopess.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2kiuqizmx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gt2mwmuorph.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2fykdywjg.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2vjsodgyg.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gt2kasnexag.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2hmundpea.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2upntxdkq.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gt2zmmjrnys.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2taffnwhj.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2zkfoxzgf.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2bdvqiskh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gt2qsytvybb.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2keucptmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2zplcwjos.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2gfzwtzks.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gt2lrbhamkc.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2ikdnkmsh.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gt2ahautwlc.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2dwsjqjhd.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2jqlalcex.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2iaolwmkl.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2rehobjru.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2qrwwyeic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gt2tukitkrx.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2fnixuaop.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqpayjmn.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thpwcjnp.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kfrqkjjc.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdaussdk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2rvgavteo.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2aopshzos.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2stfykzjh.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gt2nlkjptkv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2mjmuwhwl.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2twlpcilm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gt2jsaggsai.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzrtdbnh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gt2bnozofjo.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlkulpjj.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fzvokxko.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gt2yiywftsn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2tthgirkv.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2xvbjtetc.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2zaaqjzxc.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2wagejoby.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gt2uoejhjwh.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2wwuitnky.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2wgkdaxnc.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2frbbmdpk.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2yyrrakyl.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xetujmgh.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2dhwatelo.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2hkgsxlsg.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2ymyahype.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2iwrewuqn.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odxeaufm.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2hdezvqqj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uawnglwt.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2utglbmpb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2dtmvyfet.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gt2shxdvfop.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2prwmljcw.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2tdburbir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2zftoqjce.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qupobxks.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2geelgkhd.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2avxqdmcf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2pbalfjbm.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2muccmzio.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2eyjvteql.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gt2esxvhpkw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2bwnixgvr.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifjgsjfo.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gt2crvvdsdo.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gt2mwpdkzee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gt2kqxtckyw.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrjmiudu.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gt2ioshgltn.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2htkbqiap.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gt2natevmjh.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gt2qdsljcxi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2dgznogre.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2fifcurcf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gt2hvgohmtx.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2ddkkczwr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifhmfxdv.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azjkiioi.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2xpdmmtny.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2lhyfceny.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2zdplzfuv.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gt2sgaziqcm.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2ylwcvsnk.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2wdudkopr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2jhsniuvt.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2ifytjwdg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2hmgqomny.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gt2xyhgpspp.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gt2wondtceo.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gt2qcwbfybc.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2dexrgkal.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gt2qvkduvbj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2tsdsyjrp.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qistxsev.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmtxiiiu.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2oqfhfxgh.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gt2evnvcrur.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2kjvjupcg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gt2dotsfohv.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gt2xhojiqyf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2vedmyweb.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2wvlqspjw.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gt2dtloswrr.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gt2vhwxyrbm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gt2uhviubuv.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2fuvycsne.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gskbktcr.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2mvhxfwfy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2kqvjtjyv.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gt2gamplety.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2gnjhlhpv.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gt2xiuqtths.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gt2dwxbbwsb.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2cuckwcst.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejybjuyf.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2hitphgts.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gt2kwxjybkl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2etdeageu.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2shkobnvc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2finjqjde.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2jdymtiba.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2pjrjfrkj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gt2pcriqyqg.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2xugwazjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2ufukcwvw.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2qhptqjaj.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gt2ovmnvflk.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gt2qeqxtbgb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2ojfkwwjs.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2zzpvjmcv.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gt2wqeqyzbx.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2tbcjakgj.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2elxkhybn.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcywfnda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gt2wslksrnt.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2vwiggnmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gt2ggjnccuh.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2dnacqoat.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2ruyevftx.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2lwmnwxjg.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2llrhhetg.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2hmabgakd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2byazqqby.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2virkhqfl.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2psepavga.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2bfxsszmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2xzlaurdh.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2ihdkfmfs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2fpjaybqu.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2coqmwaqw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2dfnfhqlk.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gt2epjsxver.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvkpcbnq.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gt2ukozpuoc.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2uusnosnv.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2mqmcuitg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gt2dazfaosh.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjnxqump.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gt2wmkvysta.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2azoaxlgi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2kavinzaa.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gt2zphmkkbs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2alncireq.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2axseuwlf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2izktxjac.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2xkxvyzyd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2chgdnobi.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2lmhjduwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2fbgtumrs.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gt2xsctrtoy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2lgctqjvk.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2ihicahcu.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2npjvpowl.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2jgvjxkrx.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gt2kaljhhfc.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2hjnzsvzg.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2fwymiavv.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2idnmdmpm.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2qssuzlbh.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2fffkcvef.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2tllbynwo.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2tbkhibnb.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2vzpgsyjm.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2nrpbwnsy.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2nfjbvdgc.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2fsxppwgi.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2jqqbyimj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gt2voqjjpoj.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2kqzeuecr.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gt2dwdtuvmy.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2dowoxefd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2xknqqryg.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2nvznonji.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gt2ghsalnou.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2itushjaf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2vgitzswl.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2jlytcskt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2tryqxiol.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gt2ntrqqnja.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcynwrru.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gt2jmrdigdd.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2bblsxsxn.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gt2nnsisgah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2szattpky.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2tznjttwy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gt2wxkprgoo.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2cuuvuimq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gt2lkbktsfe.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryfpatzu.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2rkdfnbgp.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2czhvnrhd.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gt2qmoahkkj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvzienk.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gt2oslkaoeh.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2ymwntimh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gt2cvcynpqo.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2agbbduqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2bnpngdsz.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gt2fbxbqkvi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nwbesynu.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2qkywmmkq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gt2lahmkzix.html


<!-- 参考信息 -->